# AddressForge

AddressForge is a web app that lets you create Ethereum smart contracts at specific addresses with leading zeros or custom patterns. This can lower your gas costs or improve your address aesthetics.

## Features

- User-friendly interface that is easy to use right away.
- Optimized to find the desired address with minimal effort and time.
- Uses Golem Network, a decentralized platform that provides computing power for finding the specific addresses you want.

## How to use

To use AddressForge, you need to:

- Activate and commect plug-in and select whether you want to reduce gas costs or edit the address of your contract.
- Set the number of leading zeros or the custom pattern (with '0x' prefix) you want in your contract address, up to 20 hexadecimals only.
- Enter the address of the deployer account that will create the contract.
- Connected wallet will be charged for the transaction fees and the Golem Network fees. You will need to have some GLM tokens in your wallet to use the Golem Network service and native token of blochkchain on witch You deploy contract.
- Start the process of finding and deploying your contract. AddressForge will use the Golem Network to generate and test many addresses until it finds one that matches your criteria. It will then deploy the contract to that address and show you the result. You can check and use your contract on Ethereum.

## Technologies used

- <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/35px-React-icon.svg.png" alt="React Logo"> [React](https://reactjs.org/) - A JavaScript library for building user interfaces.

## Backend Technologies

- <img src="https://expressjs.com/images/favicon.png" alt="Express.js Logo" height="35"> [Express.js](https://expressjs.com/) - A fast, unopinionated, minimalist web framework for Node.js.
- <img src="https://remix.ethereum.org/icon.png" alt="Remix IDE Logo" height="35"> Remix IDE - Remix IDE is an open-source, integrated development environment for Ethereum, enabling the writing, testing, and deployment of smart contracts in Solidity and other blockchain languages.


- - <img src="https://cryptologos.cc/logos/golem-network-tokens-glm-logo.png" alt="Golem Logo" height="35"> [Golem Network](https://golem.network/)  Golem Network for the decentralized computing power.


## Libraries

- [@remixproject/plugin-webview](https://github.com/bunsenstraat/remix-plugin-docs/blob/master/docs/plugin/packages) - A library for creating plugins for the Remix IDE, enabling webview integration for enhanced development workflows within the Ethereum ecosystem.
- [env](https://www.npmjs.com/package/dotenv) - Library for loading environment variables from a .env file.
- [axios](https://axios-http.com/) - Promise-based HTTP client for making API requests.
- [express](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js.

## Getting Started

### Installation

1. Clone this repository: `git clone https://github.com/Grandpa1001/AddressForge.git`
2. Navigate to the project directory: `cd address-forge`
3. Install frontend dependencies: `npm install`

### Usage

1. Start the frontend development server: `npm run dev`
2. Open your web browser and navigate to the provided Vite URL: `http://localhost:XXXX`

## Contributors

- Aleksander Morawski
- Krzysztof Wesołek
- Franek Krawczyk
- Kamil Bandzwołek
- Jakub Skwierawski

## Contributing

We welcome contributions from anyone who is interested in improving AddressForge. Please follow these steps to contribute:

- Fork this repository and clone it to your local machine.
- Create a new branch for your feature or bug fix.
- Make your changes and commit them with a clear and descriptive message.
- Push your branch to your forked repository and create a pull request.
- Wait for a review and feedback from the maintainers.


## License

This project is licensed under the [MIT License](https://www.mit.edu/~amini/LICENSE.md).

---

This project was originally made for Degenhack and applied for the following bounties:
