# Webpack Starter

A minimal and efficient boilerplate for building modern web applications using Webpack. This starter project provides a solid foundation with hot reloading, ES6+ support, and optimized build configurations, making it ideal for rapid development and prototyping.

## 🚀 Features

- **Hot Module Replacement (HMR)**: Instant updates during development without full page reloads
- **ES6+ Support**: Transpile modern JavaScript with Babel for broad browser compatibility
- **CSS Extraction**: Separate CSS files for production builds to improve loading performance
- **Development Server**: Built-in dev server with automatic browser opening and compression
- **HTML Template**: Dynamic HTML generation with customizable templates
- **Clean Build Output**: Organized dist folder with bundled assets

## 🛠️ Technologies Used

- **Webpack 5**: Module bundler with advanced optimization features
- **Babel**: JavaScript transpiler for modern syntax support
- **CSS Loaders**: Style processing and extraction for production
- **HTML Webpack Plugin**: Automatic HTML file generation
- **Webpack Dev Server**: Development server with live reloading

## 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/philipstubbs13/webpack-starter.git
   cd webpack-starter
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## 🏃 Usage

### Development

Start the development server with hot reloading:

```bash
npm run dev
```

This will open your browser at `http://localhost:3000` and automatically reload on file changes.

### Production Build

Create an optimized production build:

```bash
npm run build
```

The built files will be in the `dist/` directory, ready for deployment.

## 🔧 Configuration

The Webpack configuration includes:

- Entry point: `src/index.js`
- Output: `dist/bundle.js`
- Development server on port 3000
- CSS extraction for production builds
- Babel transpilation for JavaScript

Customize `webpack.config.js` to fit your project's specific needs.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
