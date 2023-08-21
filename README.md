# ERC20 Presale-Vesting Contract with Truffle

The ERC20 Presale-Vesting Contract is a comprehensive smart contract solution for managing token distribution during presales with an integrated vesting mechanism. This contract ensures a secure and transparent process for releasing ERC20 tokens to investors over time, enhancing trust and fairness in token distribution.

## Features

- **Presale Token Locking**: Securely locks ERC20 tokens during the presale phase, preventing immediate transfer and ensuring adherence to vesting terms.

- **Vesting Schedule**: Gradually releases tokens to investors based on a predetermined vesting schedule, encouraging responsible token usage and long-term commitment.

- **Flexible Configuration**: Customize vesting periods, cliff durations, and other parameters to tailor the contract to your specific project requirements.

- **Transparent Process**: The contract's logic is executed on the blockchain, ensuring transparency and immutability that stakeholders can independently verify.

- **Investor Confidence**: Clear vesting schedule instills investor confidence by assuring them of gradual token release, mitigating the risk of market oversaturation.

## Usage with Truffle

1. Clone this repository.

2. Install required dependencies: `npm install`.

3. Configure the contract by adjusting the constructor parameters and other settings in the `contracts/ERC20PresaleVesting.sol` file.

4. Compile the contract using Truffle: `truffle compile`.

5. Deploy the contract to your desired blockchain network using Truffle migrations: `truffle migrate --network <network_name>`.

6. Interact with the deployed contract through Truffle's console or scripts to manage the presale, vesting, and token releases.

## Getting Started

1. Clone this repository: `git clone <repository_url>`.

2. Install Truffle globally: `npm install -g truffle`.

3. Navigate to the project directory: `cd ERC20-Presale-Vesting-Contract`.

4. Install required dependencies: `npm install`.

5. Configure the contract in the `contracts/ERC20PresaleVesting.sol` file.

6. Compile the contract: `truffle compile`.

7. Deploy the contract: `truffle migrate --network <network_name>`.

8. Interact with the contract using Truffle's console or scripts to manage different aspects of the contract.

## Contributions

Contributions to this repository are encouraged! If you encounter issues or wish to contribute enhancements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Disclaimer: This contract template is provided as-is and should be thoroughly reviewed and tested before deployment. It may not cover all use cases, and modifications may be necessary to suit specific project requirements.
