# X UI Clone

A high-fidelity user interface replica of X built with Tailwind CSS v4.

## 🚀 Features

* **Responsive Design:** Fluid layout across mobile, tablet, and desktop viewports using Tailwind's utility-first breakpoints.
* **Semantic Structure:** Structured with modern HTML5 layout tags (`<aside>`, `<main>`, `<section>`) for optimal web standards.
* **Dynamic Feed Elements:** Replicates complex UI elements including sticky navigation sidebars, custom scroll mechanics, hover state transitions, and responsive modal structures.
* **Local Media Organization:** Clean asset segregation dividing user profile imagery from timeline feed attachments.

## 🛠️ Tech Stack

* **HTML5:** Semantic architecture and structures.
* **Tailwind CSS:** Utility-first framework configuration.
* **Node.js & npm:** Build process management and asset compilation pipeline.

## 📁 Project Structure

The project maintains a modular, standard front-end directory structure:

```plaintext
├── assets/
│   └── img/
├── css/
│   └── style.css             # Compiled Tailwind production styles
├── src/
│   └── input.css             # Tailwind source entry point with custom directives
├── favicon.ico               # Site branding shortcut icon
├── index.html                # Main application view file
├── package-lock.json         # Automated npm dependency locking
└── package.json              # Project dependencies and compilation scripts
```

## ⚡ Quick Start

Follow these steps to run the development server locally:

### 1. Clone the Repository

```bash
git clone https://github.com/ayanattaarbab/x-ui-clone.git
cd x-ui-clone

```

### 2. Install Dependencies

Initialize the node modules required for the Tailwind compiler process:

```bash
npm install

```

### 3. Run the Build Script

Compile the Tailwind file from your source folder to the distribution stylesheet:

```bash
npm run build

```

### 4. Launch the Application

Open `index.html` directly in your browser or run it through a local server utility like Live Server in VS Code.
