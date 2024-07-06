# SCSS with Webpack

<div align="center">
<img src="https://webpack.js.org/assets/icon-square-big.svg" width="200">
<img src="https://sass-lang.com/assets/img/logos/logo.svg" width="240">
</div>

This project demonstrates how to use Webpack to compile SCSS files automatically whenever changes are made.

## Project Structure

```paintext
project-root/
├── dist/
│ └── index.html
├── src/
│ ├── index.js
│ └── scss/
│ └── main.scss
├── package.json
└── webpack.config.js
```


## Prerequisites

Ensure you have Node.js and npm installed. If not, download and install them from [Node.js official website](https://nodejs.org/).

## Setup Instructions

**Install dependencies**:
```bash
npm install
```

- `npm run build`: Compile the SCSS and JavaScript files once.
- `npm run watch`: Watch for file changes and recompile automatically.