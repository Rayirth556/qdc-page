# Website - Login Page

A simple login page built with Tailwind CSS.

## Project Structure

```
website/
├── public/
│   └── index.html          # Main HTML file
├── src/
│   └── input.css           # Tailwind CSS input file
├── dist/
│   └── output.css          # Compiled CSS (generated)
├── package.json            # NPM configuration
├── tailwind.config.js      # Tailwind configuration
└── README.md              # This file
```

## Getting Started

### Prerequisites
- Node.js and npm installed

### Installation
```bash
npm install
```

### Development
Start the development server with live reload:
```bash
npm run dev
```
This will start a live server on http://localhost:3000

### Build
Build the CSS for production:
```bash
npm run build
```

### Watch Mode
Watch for changes and rebuild CSS automatically:
```bash
npm run build-css
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build CSS for production
- `npm run build-css` - Watch and rebuild CSS
- `npm start` - Start both CSS watcher and dev server

## Features

- Simple, clean login form
- Responsive design
- Tailwind CSS styling
- Basic form validation
- Remember me checkbox
- Forgot password link
- Sign up link

## Technologies Used

- HTML5
- Tailwind CSS
- Live Server (for development)