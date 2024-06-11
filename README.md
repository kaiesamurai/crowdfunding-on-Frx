# FrxRise Crowdfunding DApp

Revolutionize the way projects and ideas are funded with our blockchain crowdfunding DApp built on the Frax Testnet. This innovative platform leverages the power of blockchain technology to create a decentralized, transparent, and secure environment for fundraising.

Our crowdfunding DApp enables project creators to raise capital directly from a global pool of investors without the need for intermediaries. By utilizing smart contracts, the DApp automates the fundraising process, ensuring that funds are released to project creators only when predefined milestones are met, thereby increasing accountability and reducing the risk of fraud.

## Future Scope

- **Connecting with IPFS**: We can connect our contract with IPFS, allowing creators to deploy images and progress of their projects without storing this data on the blockchain.
- **Report Functionality**: Implement a report functionality where donors can report instances where project creators fail to fulfill their promises. Upon verification, the project creator's ID will be banned from creating another campaign.
- **Fees Charging for Uploading**: Introduce a fee for uploading projects onto the platform.
- **Security Deposit**: Require a 5% security deposit when submitting a project, refunded upon successful completion.
- **Multichain Functionality**: Enable users from different blockchain networks to donate to projects.
- **Additional Features**: Active Donators Award System, Project Advertisement (Featured Projects), Tiers/Multiple Donation Amount Options, KYC, etc.

## Getting Started with Our DApp (Local Host Using Hardhat)

1. **Install all dependencies**:
    ```bash
    npm install
    ```

2. **Run the Hardhat local node**:
    ```bash
    npx hardhat node
    ```

3. **Deploy the contract on the local network**:
    ```bash
    npx hardhat run --network localhost scripts/deploy.js
    ```

4. **Update the CrowdFunding.json file**:
    - This will generate two folders: `artifacts` and `cache`.
    - Delete the `CrowdFunding.json` file from the `Context` folder.
    - Go to `artifacts/contracts`, copy the new `CrowdFunding.json` from there, and paste it into the `Context` folder.

5. **Run the development server**:
    ```bash
    npm run dev
    ```

## Deployed on Frax Testnet

- **Contract Address**: 0x20582f1aA08b61143990dEB9820fc8e436730f0C
- **Verified Contract**: [Frax Testnet Verification](https://holesky.fraxscan.com/address/0x20582f1aA08b61143990dEB9820fc8e436730f0C)
https://holesky.fraxscan.com/address/0x20582f1aA08b61143990dEB9820fc8e436730f0C

Thank you for using our FrxRise Crowdfunding DApp.