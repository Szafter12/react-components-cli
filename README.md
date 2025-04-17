# ⚛️ react — CLI for generating React components

A simple Bash script that helps you quickly scaffold React components inside the `src/components` directory. Supports both JSX and TypeScript (TSX) with modular CSS.

## ✅ Features

- Creates a folder `src/components/ComponentName`
- Generates `ComponentName.jsx` or `ComponentName.tsx`
- Generates `ComponentName.module.css`
- Supports TypeScript via the `--ts` flag
- Works globally with the `react make:component` command

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Szafter12/react-components-cli.git
```

### 2. Navigate into the directory

```bash
cd react-component-cli
```

### 3. Make the script executable

```bash
chmod +x react
```

### 4. (Optional) Install it globally - This allows you to use the react command globally from anywhere in your terminal.

```bash
sudo cp react /usr/local/bin/react
```

## 💡 Usage

### Create a JSX component

```bash
react make:component Button
```

This will generate

```css
src/components/Button/
├── Button.jsx
└── Button.module.css
```

### Create a TSX component (for TypeScript projects)

```bash
react make:component Button --ts
```

This will generate:

```css
src/components/Button/
├── Button.tsx
└── Button.module.css
```

## 🪟 Windows — How to use it?

### ✅ Requirements
- [Git for Windows](https://git-scm.com/downloads/win)
- Use Git Bash (installed automatically with Git)

### ✅ Steps
- Open Git Bash
- Follow the installation steps (clone, make executable)
- Open Git Bash and edit your .bashrc or .bash_profile:
  
```bash
nano ~/.bashrc
```

- Add a line like this (replace the path with where your script is) - Remember to use Unix-style paths (/c/Users/...) in Git Bash:
  
```bash
export PATH="$PATH:/c/path_to_folder_with_script"
```

- Save and reload:

```bash
source ~/.bashrc
```

Now you can run:

```bash
react make:component Button
```

