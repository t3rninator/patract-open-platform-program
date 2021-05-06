# [Phala](https://phala.network/)

## Project Introduction

Phala Network is a privacy-preserving cloud computing service, based on Substrate, and will run as a parachain in the Polkadot ecosystem to offer computing power comparable to existing cloud services but which protects the privacy of managed programs. Based on TEE-Blockchain Hybrid Architecture, developers can deploy confidential smart contracts running inside Secure Enclaves in CPUs.

## Wasm contract technical support

Phala Network adopts WASM-based confidential contracts, and will support Ink! smart contract as the confidential contract language. Phala Network will integrate the confidential contract to Patract's Redspot toolchain for developers to easily build, test, and deploy on Phala Network.

Unlike other blockchains, the transaction and states of Phala confidential contracts are encrypted by default. It serves as a confidential layer for other blockchains via cross-chain bridges and XCMP.

Phala team is working on the confidential contract WASM runtime. It passed the early test vectors, but is still being developed for production level use:

- <https://github.com/Phala-Network/pink-sgx>
- <https://github.com/Phala-Network/wasmi-sgx>

The existing native confidential contracts will be migrated to Ink! soon:

<https://github.com/Phala-Network/phala-blockchain/tree/master/standalone/pruntime/enclave/src/contracts>

## Developer activity

Phala Network will start promoting WASM-based Confidential Contracts by releasing tutorials, documentations, and hosting Hackathons in 2021 H2.
