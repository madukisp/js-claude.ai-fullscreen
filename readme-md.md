# Claude AI Desktop App

This is an Electron-based desktop application that allows you to access Claude AI in a standalone window. It provides a fullscreen experience and comes with window control functionalities such as minimize, maximize, and close.

## Features

- Access Claude AI in a dedicated desktop window
- Fullscreen mode for an immersive experience
- Window control buttons for minimize, maximize, and close
- Easy to use and navigate

## Prerequisites

Before running the application, ensure that you have the following installed:

- Node.js (version X.X.X or higher)
- npm (version X.X.X or higher)

## Installation

1. Clone the repository or download the source code:
   ```
   git clone https://github.com/your-username/claude-ai-desktop-app.git
   ```

2. Navigate to the project directory:
   ```
   cd claude-ai-desktop-app
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Package the application:
   ```
   npm run package
   ```

5. The packaged application will be available in the `dist` directory.

## Usage

1. Run the application by executing the generated executable file in the `dist` directory.

2. The Claude AI website will load in a standalone window.

3. Use the window control buttons to minimize, maximize, or close the application.

4. Interact with Claude AI as you would in a web browser.

## Configuration

- If you want to change the default window size, modify the `width` and `height` values in the `main.js` file.

- To use a different icon for the application, replace the `icon.ico` file with your desired icon file and update the `--icon` flag in the `package` script in the `package.json` file.

## Building for Other Platforms

By default, the application is packaged for the Windows platform. If you want to package the application for other platforms (e.g., macOS or Linux), modify the `--platform` flag in the `package` script in the `package.json` file.

For example, to build for macOS, use `--platform=darwin`, and for Linux, use `--platform=linux`.

## Troubleshooting

If you encounter any issues while running or packaging the application, try the following:

- Make sure you have the latest versions of Node.js and npm installed.
- Delete the `node_modules` directory and run `npm install` again.
- Check the console for any error messages or logs.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Electron](https://www.electronjs.org/)
- [Claude AI](https://www.anthropic.com/)

If you have any questions or need further assistance, please feel free to contact me.

Happy coding!
