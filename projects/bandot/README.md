# [Bandot](https://www.bandot.io/)

## Project Introduction

Bandot is Polkadot's unsecured lending system, dedicated to building a new paradigm liquidity aggregation platform. The Bandot team built a credit delegation lending pool strategy based on the **WASM** smart contract. Depositors obtain income by depositing encrypted assets (for example: KSM/DOT/stable coins) into the lending pool to provide liquidity. At the same time, the funds in the lending pool can be lent to the borrower without collateral by way of credit delegation.

## Wasm contract progress

Bandot **Unsecured Lending Wasm contracts**  consists of the following parts:

* Lending Pool contract, provide the deposit, withdraw, borrow, repay functionalities;
* Tokenization contract, provide interest-bearing tokens and interest-accruing tokens;
* Oracle contract,  to provide the price of supported asserts;
* Credit evaluation contract, to provide credit delegation and control the risks of unsecured lending.

At present, with Patract [Redspot](https://github.com/patractlabs/redspot) tool, Bandot team have created a simple credit delegation lending system by using the a rough KYC verification, and deploy it into Patract [Jupiter](https://github.com/patractlabs/jupiter) test network. At the same time, team completed the feasibility analysis of calling openlaw, investigated the chainlink-pallet, and began to design the Oracle contract.

## Developer activity

Currently, Polkadot Wasm contract development ecosystem is in the early stage, so Bandot team will:

* Continue to actively participate in the Wasm contract guidance course provided by the Patract team for developers, learn and accumulate **ink!** development experience, and apply it to the development of the unsecured lending system;
* At the same time, we will maintain communication with other development teams in the **Open Platform**.
