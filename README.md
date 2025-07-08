# The Secret Lives of Quantum

An interactive visualization that teaches quantum computing concepts through hands-on exploration, inspired by [The Secret Lives of Data](https://thesecretlivesofdata.com/raft/).

![Quantum Computing Visualization](https://img.shields.io/badge/Quantum-Computing-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Overview

This educational tool breaks down complex quantum computing concepts into digestible, interactive lessons. Through 20 progressive steps across 7 chapters, users learn about:

- **Classical Computing**: Bits, binary representation, and ASCII encoding
- **Quantum Fundamentals**: Qubits and the Bloch sphere
- **Quantum Properties**: Superposition and measurement
- **Quantum Gates**: X, H, and Z gate operations
- **Quantum Entanglement**: Creating and measuring entangled qubits
- **Quantum Advantage**: Why quantum computing matters and real-world applications

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- No installation or build process required!

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/secret_lives_of_quantum.git
   cd secret_lives_of_quantum
   ```

2. Open the application:
   - **Option 1**: Double-click `index.html` in your file explorer
   - **Option 2**: From the command line:
     ```bash
     # On macOS
     open index.html
     
     # On Linux
     xdg-open index.html
     
     # On Windows
     start index.html
     ```

3. That's it! The application will open in your default browser.

### Using a Local Web Server (Optional)

For the best experience, you can serve the file using a local web server:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

## How to Use

1. **Start the Journey**: The tutorial begins automatically with classical computing concepts
2. **Interactive Learning**: Click "Try It" to interact with each concept and see immediate results
3. **Navigate**: Use "Next Step" and "Previous Step" buttons to move through lessons
4. **Progress Tracking**: Watch the progress bar and "Step X of 20" indicator
5. **Experiment**: Many visualizations are interactive - click on qubits, gates, and other elements

### Learning Path

The tutorial progresses through 7 chapters:

1. **Classical Computing** (Steps 1-3): Understanding bits and binary
2. **Introduction to Quantum** (Steps 4-7): The Bloch sphere and quantum states
3. **Quantum Qubits** (Step 8): Transitioning from theory to practice
4. **Quantum Gates** (Steps 9-12): X, H, and Z gate operations
5. **Quantum Measurement** (Steps 13-14): Superposition collapse and randomness
6. **Quantum Entanglement** (Steps 15-16): Creating and measuring entangled qubits
7. **Quantum Advantage** (Steps 17-19): Real-world applications and why quantum matters

## Features

- 🎯 **Progressive Learning**: 20 carefully crafted steps from classical to quantum computing
- 🎨 **Visual Representations**: 3D Bloch sphere, qubit states, entanglement visualization, and gate operations
- 🔄 **Interactive Elements**: Hands-on manipulation of quantum states with immediate visual feedback
- 📊 **Binary Visualization**: See how classical bits form human-readable ASCII characters
- ⚡ **No Dependencies**: Pure HTML/CSS/JS - works anywhere
- 🌙 **Dark Theme**: Easy on the eyes with quantum-inspired aesthetics
- 🔗 **Entanglement Demo**: Visual representation of quantum entanglement with connected qubits
- 🚀 **Quantum Advantage**: Learn why quantum computers outperform classical computers for certain problems

## Project Structure

```
secret_lives_of_quantum/
├── index.html      # Complete application (HTML + CSS + JavaScript)
├── README.md       # This file
└── CLAUDE.md       # Development guide for AI assistants
```

## Deployment

Since this is a static HTML file, deployment is straightforward:

### GitHub Pages
This project is already configured to deploy to GitHub Pages!

🌐 **Live Demo**: [https://two-bear-capital.github.io/secret_lives_of_quantum/](https://two-bear-capital.github.io/secret_lives_of_quantum/)

To update the deployment:
1. Make your changes locally
2. Push to the main branch
3. GitHub Pages will automatically update within a few minutes

### Any Web Server
Simply copy `index.html` to your web server's public directory.

### Netlify Drop
1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag and drop the `index.html` file
3. Get an instant URL

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open source and available under the [MIT License](LICENSE).

Copyright (c) 2024 Two Bear Capital

## Acknowledgments

- Inspired by [The Secret Lives of Data](https://thesecretlivesofdata.com/) visualization approach
- Built with pure web technologies for maximum accessibility
- Designed to make quantum computing concepts approachable for everyone

---

🚀 **Ready to explore the quantum realm?** Open `index.html` and begin your journey!