# Web3 Payment Gateway Enhancements

This npm package is designed to enhance the functionality of existing Web3 payment gateways, adding features such as real-time transaction monitoring, failover mechanisms, and support for multiple cryptocurrencies.

## Installation

You can install the package using npm:

```bash
npm install web3-payment-gway
```

Replace `web3-payment-gway` with the actual name you publish your package under.

## Features

- **Real-Time Transaction Monitoring**: Tracks the status of transactions in real-time to provide immediate feedback on transaction success or failure.
- **Failover Mechanisms**: Automatically reroutes transactions through different nodes if the primary node fails, increasing reliability.
- **Multi-Cryptocurrency Support**: Enables transactions with various cryptocurrencies beyond just Ethereum, including Bitcoin and others.

## Usage

To use this package, import it into your project:

```javascript
const web3Enhancements = require('web3-payment-gway');
```

Set up the payment gateway with necessary configurations:

```javascript
web3Enhancements.setup({
    apiKey: 'your-api-key', // Replace with your actual API key
    primaryNodeURL: 'https://mainnode.example.com',
    failoverNodeURL: 'https://failovernode.example.com'
});
```

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.

## License

Distributed under the MIT License. See `LICENSE` for more information.
