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

```bash
// Create a JSX component

react make:component Button
```

This will generate

```css
src/components/Button/
├── Button.jsx
└── Button.module.css
```


