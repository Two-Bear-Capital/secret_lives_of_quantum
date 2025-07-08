# The Secret Lives of Quantum

An interactive visualization that teaches quantum computing concepts through hands-on exploration, inspired by [The Secret Lives of Data](https://thesecretlivesofdata.com/raft/).

![Quantum Computing Visualization](https://img.shields.io/badge/Quantum-Computing-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Overview

This educational tool breaks down complex quantum computing concepts into digestible, interactive lessons. Through 16 progressive steps, users learn about:

- Classical bits vs quantum bits (qubits)
- Binary representation and ASCII encoding
- The Bloch sphere representation
- Quantum superposition
- Quantum measurement and collapse
- Quantum entanglement
- Quantum gates (X, H, Z)

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
2. **Interactive Learning**: Click "Try It" to interact with each concept
3. **Navigate**: Use "Next Step" and "Previous Step" buttons to move through lessons
4. **Progress Tracking**: Watch the progress bar and step indicators to see your advancement
5. **Experiment**: Many visualizations are interactive - click on qubits, gates, and other elements

## Features

- 🎯 **Progressive Learning**: 16 carefully crafted steps from classical to quantum
- 🎨 **Visual Representations**: Bloch sphere, qubit states, and gate operations
- 🔄 **Interactive Elements**: Hands-on manipulation of quantum states
- 📊 **Binary Visualization**: See how bits form human-readable information
- ⚡ **No Dependencies**: Pure HTML/CSS/JS - works anywhere
- 🌙 **Dark Theme**: Easy on the eyes with quantum-inspired aesthetics

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
1. Push to GitHub
2. Go to Settings → Pages
3. Select source branch and save
4. Your site will be available at `https://yourusername.github.io/secret_lives_of_quantum/`

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

## Acknowledgments

- Inspired by [The Secret Lives of Data](https://thesecretlivesofdata.com/) visualization approach
- Built with pure web technologies for maximum accessibility
- Designed to make quantum computing concepts approachable for everyone

---

🚀 **Ready to explore the quantum realm?** Open `index.html` and begin your journey!