# [Bandot](https://www.bandot.io/)

## 项目介绍

Bandot 是波卡无抵押借贷系统，致力于构建新范式流动性聚合平台。Bandot 团队基于 **WASM** 合约构建了信用委托借贷池策略，存款人通过将加密资产（例如：KSM/DOT/稳定币）存入借贷池提供流动性来获得收益。同时借贷池中的资金可以由信用委托的方式无抵押地出借给借款人。

## Wasm合约进展

Bandot **无抵押借贷 Wasm 合约**由以下部分组成：

* 借贷池合约，提供存款，提款，借贷，还款功能；
* 代币合约，提供计息代币和应计代币；
* Oracle合约，提供支持加密资产的价格；
* 信用评估合约，提供信用授权并控制无抵押贷款的风险。

目前，Bandot 团队使用Patract [Redspot](https://github.com/patractlabs/redspot) 脚手架工具，通过简易的KYC验证创建了一个简单的信用委托借贷系统，并将其部署到了Patract [Jupiter](https://github.com/patractlabs/jupiter) 测试网络，同时完成了调用openlaw的可行性分析，调研了 chainlink-pallet 并开始设计 Oracle 合约。



## 开发者活动

目前，波卡 Wasm 合约开发生态处于早期阶段，因此 Bandot 团队会：

* 继续积极参加 Patract 团队为开发者提供的 Wasm 合约指导课程，虚心学习并积累 ink! 开发经验，并将其应用到无抵押借贷系统的开发中；
* 同时会和开发平台中的其它开发团队保持交流沟通。
