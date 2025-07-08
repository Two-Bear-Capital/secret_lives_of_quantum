# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an interactive educational web application called "The Secret Lives of Quantum" that teaches quantum computing concepts through visualization and hands-on interaction. The entire application is contained in a single `index.html` file with inline CSS and JavaScript.

## Development Commands

This is a static HTML application with no build process:
- **Run**: Open `index.html` directly in a web browser
- **Deploy**: Copy `index.html` to any web server
- **Test**: Manual testing in browser (no automated tests)

## Architecture

### Single-File Structure
The entire application lives in `index.html` with three main sections:
1. **CSS** (lines ~7-424): Defines all styles including animations, component appearances, and responsive layout
2. **HTML** (lines ~427-503): Contains the DOM structure with visualization containers and controls
3. **JavaScript** (lines ~506-end): Implements all interactivity and state management

### Key Components

**Visualization Elements:**
- Classical bit display (`#classical-bit`)
- Binary representation display (`#binary-display`) - shows 8-bit ASCII encoding
- Bloch sphere (`#bloch-sphere`) - 3D representation of qubit states
- Quantum qubits (`#main-qubit`, `#second-qubit`)
- Quantum gates (`#gate-x`, `#gate-h`, `#gate-z`)
- Entanglement visualization (`#entanglement-line`)

**State Management:**
- `currentStep`: Tracks progress through 16-step tutorial
- `isEntangled`: Boolean for entanglement state
- `stepContent`: Object containing all tutorial content and actions

### Tutorial Flow

The application guides users through 16 steps across 4 chapters:
1. **Classical Computing** (Steps 1-3): Bits and binary representation
2. **Introduction to Quantum** (Steps 4-7): Bloch sphere and qubit states
3. **Quantum Qubits** (Steps 8+): Practical qubit manipulation
4. **Advanced Topics**: Measurement, entanglement, and quantum gates

### Key Functions

- `nextStep()`/`prevStep()`: Navigation through tutorial
- `setBinaryPattern(char)`: Displays ASCII character in binary
- `setBlochVector(position)`: Updates Bloch sphere visualization
- `setMainQubit(state)`: Updates qubit visual state
- `createEntanglement()`: Visualizes quantum entanglement
- `applyGate(gateName)`: Applies quantum gate operations

## Development Notes

When modifying this application:
- All changes should be made to `index.html`
- Maintain the educational flow and visual consistency
- Test animations and transitions across different browsers
- Ensure mobile responsiveness for educational accessibility
- The step progression (`totalSteps = 16`) must match the number of steps defined in `stepContent`