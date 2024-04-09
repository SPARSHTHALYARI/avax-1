# avax-1

## Deploying EVM Subnet and Testing Smart Contracts on Avalanche

## Prerequisites:
- Avalanche CLI installed and configured
- Metamask installed in your browser
- Remix IDE for Solidity development
- Basic understanding of Avalanche and Ethereum development

## Steps:

1. **Deploy EVM Subnet using Avalanche CLI:**
   - Follow the instructions provided by Avalanche to set up and deploy an EVM subnet using the Avalanche CLI.

2. **Add EVM Subnet to Metamask:**
   - Open Metamask in your browser.
   - Click on the network dropdown and select "Custom RPC".
   - Enter the network details provided during the EVM subnet deployment (e.g., RPC URL, Chain ID).
   - Save the network configuration.

3. **Connect Remix to Metamask:**
   - Open Remix IDE.
   - Go to the "Settings" tab.
   - Under "Plugin Manager", enable "Solidity Compiler".
   - Under "Plugin Manager", enable "Solidity Unit Testing".
   - Under "Plugin Manager", enable "Solidity Static Analysis".
   - Under "Plugin Manager", enable "Deploy & run transactions".
   - Under "Deploy & run transactions", select "Injected Web3" as the environment.
   - Remix will automatically detect and connect to Metamask.

4. **Deploy Smart Contracts:**
   - Write your smart contracts in Remix or import existing ones.
   - Compile your contracts using the Solidity Compiler in Remix.
   - Switch to the "Deploy & run transactions" tab.
   - Select the contract you want to deploy.
   - Choose the account from Metamask you want to deploy with.
   - Click on "Deploy" to deploy the contract to the EVM subnet.

5. **Testing Your Application:**
   - After deploying the contracts, you can interact with them directly from Remix.
   - Switch to the "Deploy & run transactions" tab.
   - Select the contract you deployed from the dropdown.
   - Interact with the contract's functions and transactions using Remix's interface.
   - Use the Metamask extension to confirm transactions.

6. **Additional Steps:**
   - Write unit tests for your smart contracts using Remix's Solidity Unit Testing plugin.
   - Perform static analysis on your contracts using Remix's Solidity Static Analysis plugin.

## Notes:
- Make sure to secure your accounts and private keys.
- Always verify the details of transactions before confirming them.
- Test thoroughly before deploying contracts to production environments.
- Refer to official documentation for Avalanche, Metamask, and Remix for more detailed instructions and troubleshooting.
- - -
