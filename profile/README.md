> ‼️ **The WAX project has been sunsetted by PSE and further developments have been paused as of September 2024.** ‼️ 
>
> **When WAX (formerly BLS Wallet and Hubble) started, Account Abstraction and BLS signature aggregation were relatively underdeveloped areas in the Ethereum ecosystem. But fast-forward to 2024, and the Account Abstraction ecosystem has made major progress. And since the introduction of data blobs, the cost savings from using BLS signature aggregation have decreased significantly. The work on BLS signature aggregation and compression will be valuable when the economics of Ethereum change and data availability becomes more expensive. For now, the data availability savings are not offset by the L2 execution gas costs of doing the signature aggregation.**
>
> You can read more about our work on compression here:
> * [The Impact of Blobs on Compression](https://hackmd.io/@voltrevo/ryuK6ZSR6)
> * [4337 Compression in WAX](https://hackmd.io/@voltrevo/Bkz8syuUp)
>
> We also built a handy [fee calculator](https://andrewmorris.io/wax-fee-calculator/) for measuring savings from compression

<div align="center">
    <h1>WAX: Wallet Account eXperiments (formerly BLS Wallet) 🍯</h1>
    <p>Helping wallets, dapps, and SDKs shine.</p>
</div>

## What is WAX?

WAX will be a set of production-ready smart account components providing advanced features that can be easily utilized by wallets, SDKs, and dApps.

WAX components are designed to incorporate advanced cryptographic primitives in a secure and intuitive way. The smart contracts use Safe contracts to provide a familiar and battle-tested foundation. Each additional module will be audited, and can be added and removed from the account at the account holders discretion. The accounts can be used directly, or via the 4337 mempool.

The lower level components are brought together in an easy-to-use node module - [EthDK](https://github.com/getwax/ethdk).

## Features

- ✨ Cheaper L2 transactions with BLS Signature aggregation
- 🏗️ Modular smart contract components using battle-tested [Safe modules](https://docs.safe.global/learn/safe-core/safe-core-protocol/modules)
- 📝 ERC 4337 compatible
- 📩 [zk email](https://github.com/zkemail) verification
- 🔑 passkeys verification
- 🔗 Multi-action transactions
- ⛽️ Gasless transactions
- 🔧 Wallet upgradability

Check out the components and examples in our [monorepo](https://github.com/getwax/wax).

Wallet Account eXperiments (WAX) is part of Privacy & Scaling Explorations (PSE), a multidisciplinary team supported by the Ethereum Foundation. PSE explores new use cases for zero knowledge proofs and other cryptographic primitives.
