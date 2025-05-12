
📁 alx-react/0x00-Webpack/README.md

```markdown
# 0x00 - Webpack

This project introduces Webpack — a powerful module bundler for modern JavaScript applications. You'll learn how to set up Webpack from scratch, configure loaders and plugins, split code into modules, and use a dev server.

## Learning Objectives

By the end of this project, you should be able to explain:

- How to set up Webpack for a basic project
- Entry points, output, and loaders
- How to add and configure plugins
- Code splitting and tree shaking
- Setting up a development server

## Environment

- OS: Ubuntu 18.04 LTS
- Node.js: 12.x.x
- Editor: VS Code / Vim / Emacs
- All files end with a new line

## Tasks Overview

### Task 0: Basic Setup

- Folder: `task_0`
- Install `webpack`, `webpack-cli` (devDependencies)
- Install `jquery` (dependency)
- Add paragraphs to `index.js` using jQuery
- Output built files to `dist/`
- No custom config file

### Task 1: Webpack with Config File

- Folder: `task_1`
- Add `webpack.config.js` with output set to `public/bundle.js`
- Use jQuery & Lodash
- Debounce click counter in JS
- Webpack build script via `npm run build`

### Task 2: Add CSS & Images

- Folder: `task_2`
- Add CSS support to Webpack config
- Use `css-loader`, `style-loader`, `file-loader` or `asset modules`
- Add a logo image and apply styles
- Optimize image bundling

### Task 3: Dev Server & Code Splitting

- Folder: `task_3`
- Set up `webpack-dev-server` on port 8564
- Split code into modules (`header`, `body`, `footer`)
- Use separate entry points and generate bundles for each
- Use plugins: `HtmlWebpackPlugin`, `CleanWebpackPlugin`
- Enable source maps for better debugging
- Enable code splitting to reduce bundle size

## Running the Project

From any task directory:

```bash
npm install       # Install dependencies
npm run build     # Build production bundle
npm run start-dev # Start dev server (task_3 only)