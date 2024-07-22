# Hardhat + React + Vite Boilerplate

Welcome to the Hardhat + React + Vite Boilerplate! This repository provides a starting point for building decentralized applications (dApps) using Hardhat for Ethereum development and React with Vite for the frontend.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Scripts](#scripts)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Hardhat**: Ethereum development environment for compiling, deploying, testing, and debugging Ethereum software.
- **React**: JavaScript library for building user interfaces.
- **Vite**: Next-generation frontend tooling. It's fast!

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js** (>= 14.x.x)
- **npm** or **yarn**

## Getting Started

1. **Clone the repository**

    ```sh
    git clone https://github.com/devansh0331/hardhat-react-vite-boilerplate.git
    cd hardhat-react-vite-boilerplate
    ```

2. **Install dependencies**

    Using npm:

    ```sh
    npm install
    ```

    Or using yarn:

    ```sh
    yarn install
    ```

3. **Start the development server**

    ```sh
    npm run dev
    ```

    Or using yarn:

    ```sh
    yarn dev
    ```

    The application should now be running on [http://localhost:5173](http://localhost:5173).

4. **Compile contracts**

    ```sh
    npx hardhat compile
    ```

## Project Structure

- **/contracts**: Ethereum smart contracts.
- **/scripts**: Deployment scripts for smart contracts.
- **/test**: Smart contract tests.
- **/src**: React application source code.


## Scripts

### Hardhat

- `yarn hardhat compile`: Compiles the smart contracts.
- `yarn hardhat test`: Runs the tests for the smart contracts.
- `yarn hardhat node`: Starts a local Ethereum node.
- `yarn hardhat deploy`: Deploys the smart contracts to the local Ethereum node.

### React + Vite

- `npm run dev`: Runs the Vite development server.
- `npm run build`: Builds the React application for production.
- `npm run serve`: Serves the built React application.
- `npm run test`: Runs tests for the React application.

## Configuration

### Hardhat

Configuration for Hardhat can be found in `hardhat.config.js`. You can customize network settings, paths, and other options here.

### Vite

Configuration for Vite can be found in `vite.config.js`. You can customize build options, plugins, and more here.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy coding! If you have any questions, feel free to open an issue.
