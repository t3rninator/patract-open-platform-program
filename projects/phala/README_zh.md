# [Phala](https://phala.network/)

## 项目介绍

Phala Network 是一个无需许可和去信任化的隐私计算云。Phala 基于 Substrate 构建，作为波卡生态系统的平行链运行，以提供与现有云服务相当的计算能力并保护托管程序的隐私。 基于Phala的TEE-区块链混合架构，开发者可以在 CPU 的安全区域内轻松部署运行 Phala 机密智能合约。

## Wasm合约进展

Phala Network 采用了基于 WASM 的保密智能合约，并且将会支持 Ink! 智能合约语言。Phala 将会为 Patract Redspot 提供保密智能合约的整合，以帮助开发者轻松的实现合约的开发、测试与部署。

与其他区块链不同，Phala Network 的保密智能合约实现了完全的交易与合约状态保密，可以通过桥和 XCMP 为其他区块链提供保密能力。

WASM 保密智能合约正在开发中，目前已经可以通过简单的 Ink! 功能性测试，正在进一步开发，实现产品级别的可用性：

- <https://github.com/Phala-Network/pink-sgx>
- <https://github.com/Phala-Network/wasmi-sgx>

目前已有的原生智能合约也即将迁移到 Ink!

<https://github.com/Phala-Network/phala-blockchain/tree/master/standalone/pruntime/enclave/src/contracts>

## 开发者活动

Phala Network 计划在主网上线、2021年H2后开始完善 WASM 智能合约的开发教程、文档，以及开展黑客马拉松等。
