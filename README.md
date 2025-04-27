
Built by https://www.blackbox.ai

---

# Dicoding Story SPA

Dicoding Story SPA is a single-page web application that utilizes Webpack as its build tool. This project serves as an example for building modern web applications while leveraging the capabilities of Webpack to bundle JavaScript modules, process stylesheets, and serve the application locally.

## Project Overview

This application is designed to demonstrate a simple yet effective use of Webpack for managing dependencies, module bundling, and development server capabilities. The application allows users to interactively explore stories through an intuitive interface.

## Installation

To get started with this project, follow the instructions below to install the required dependencies and set up the application:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/dicoding-story-spa.git
   cd dicoding-story-spa
   ```

2. **Install the dependencies**:
   Ensure you have `Node.js` (version 10 or higher) installed, then run:
   ```bash
   npm install
   ```

## Usage

After the installation is complete, you can start the development server with the following command:

```bash
npm start
```

This will start the Webpack development server and you can access the application at `http://localhost:9000` in your web browser. Any changes you make to the source files will automatically reload the application.

To build the application for production, use the following command:

```bash
npm run build
```

This will create a bundled production version of your app in the `dist` directory.

## Features

- **Hot Module Replacement (HMR)**: Automatically updates the application in the browser as you edit the source files.
- **Asset Management**: Supports importing and bundling of CSS and image assets directly in your JavaScript.
- **Dev Server**: A lightweight development server to serve the application and assets.
- **Error Reporting**: Integrated source maps for easier debugging.

## Dependencies

The following dependencies are used in this project, as specified in the `package.json` file:

- **Webpack**: 5.75.0
- **Webpack CLI**: 4.10.0
- **Webpack Dev Server**: 4.11.1
- **CSS Loader**: 6.7.3
- **Style Loader**: 3.3.1
- **Leaflet**: 1.9.3 (for map functionality)

```json
"devDependencies": {
    "css-loader": "^6.7.3",
    "style-loader": "^3.3.1",
    "webpack": "^5.75.0",
    "webpack-cli": "^4.10.0",
    "webpack-dev-server": "^4.11.1"
},
"dependencies": {
    "leaflet": "^1.9.3"
}
```

## Project Structure

Here's a brief overview of the project's structure:

```
dicoding-story-spa/
├── dist/                  # Production build output
├── src/                   # Source code
│   ├── index.js           # Main JavaScript file
│   └── styles.css         # Main CSS file
├── package.json           # Project metadata and dependencies
└── webpack.config.js      # Webpack configuration file
```

- **dist/**: Contains the production files after running the build command.
- **src/**: Contains the source code for the project including JavaScript and CSS files.
- **package.json**: Contains details about the project and its dependencies.
- **webpack.config.js**: The configuration file that defines how Webpack processes the application.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests for improvements, bug fixes, or additional features.

## License

This project is licensed under the ISC License. See the `LICENSE` file for more details.