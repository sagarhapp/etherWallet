# EtherWallet

EtherWallet is a comprehensive Ethereum wallet application designed to provide users with a secure and user-friendly experience for managing their Ethereum assets. This project includes both a web application and a Chrome extension, offering features such as wallet generation, transaction management, and support for various Ethereum networks and tokens.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
  - [Main Directory](#main-directory)
  - [App Directory](#app-directory)
  - [Chrome Extension Directory](#chrome-extension-directory)
- [License](#license)

## Installation

To set up EtherWallet Mercury, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/etherwallet-mercury.git
    cd etherwallet-mercury
    ```

2. Install the necessary dependencies:
    ```bash
    npm install
    ```

3. Build the project:
    ```bash
    npm run build
    ```

4. Start the development server:
    ```bash
    npm start
    ```

5. To build the Chrome extension, run:
    ```bash
    npm run build-extension
    ```

## Usage

- **Web Application**: Access the web version of the wallet through your browser. Use it to create and manage your Ethereum wallets, interact with smart contracts, and perform transactions.
  
- **Chrome Extension**: Install the Chrome extension for quick access to your Ethereum wallet directly from your browser toolbar.

## File Structure

### Main Directory

- `CHANGELOG.md`: Details the version history and changes.
- `Dockerfile`: Docker configuration for containerized deployment.
- `LICENSE.md`: License information.
- `README.md`: Project overview and documentation (this file).
- `gulpfile.js`: Gulp configuration for automating tasks.
- `mew.gpg.enc`: Encrypted GPG key for secure communication.
- `MEW-PUP-KEY-GPG`: Public GPG key for verification.
- `dist/`: Output directory for the built project.
- `package.json`: Project metadata and dependency list.
- `package-lock.json`: Lock file for package versions.

### App Directory

Contains the core application files:

- `fonts/`: Web fonts used in the application (e.g., Lato).
- `images/`: Image assets, including logos, icons, and backgrounds.
- `includes/`: HTML template files for different parts of the app.
- `layouts/`: HTML layout files.
- `scripts/`: JavaScript code for app functionality, including controllers, services, and utilities.
- `styles/`: LESS files for styling the application.
- `tests/`: Test files for validating the application functionality.
- `manifest.json`: Configuration file for the web application.

### Chrome Extension Directory

Contains files specific to the Chrome extension:

- `background/`: Background scripts for the extension.
- `browser_action/`: HTML files for the extension's popup.
- `css/`: CSS styles for the extension.
- `fonts/`: Web fonts used in the extension.
- `images/`: Image assets for the extension.
- `js/`: JavaScript files for the extension.
- `manifest.json`: Configuration file for the Chrome extension.

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.