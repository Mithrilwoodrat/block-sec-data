# block-sec-data
区块链安全资料

先安装钱包，eth、layer2（兼容 eth）都需要钱包交互，包括他们的测试网络。chrome 安装 metamask 插件
sol 有另外的钱包插件比如 Phantom

## 基础概念

### ETH
 - 《以太坊的指南针》 https://ethbook.abyteahead.com/index.html
 - 《Master ETH（精通以太坊）》
 - eth 源码分析 https://github.com/ZtesoftCS/go-ethereum-code-analysis
 - ETH 漏洞 https://swende.se/blog/Ethereum.html
 - eth 开发文档 https://ethereum.org/en/developers/docs/

### solana
rust的编写的公链，意图取代 eth，合约为c或rust开发

- https://github.com/solana-labs/solana
- demo 项目 https://github.com/solana-labs/solana-program-library （很多项目方基于这个改的）

### DEFI
 - [什么是DEFI(上)(]https://zhuanlan.zhihu.com/p/377856331)
 - [什么是DEFI(下)(]https://zhuanlan.zhihu.com/p/379970891)
 - https://forkit.fm/16 #16 - 和神鱼聊聊流动性挖矿

## 安全 blog
 - 慢雾公众号
 - https://lorexxar.cn/
 - https://hacked.slowmist.io/
 - https://www.slowmist.com/news.html
 - BlockSecTeam（浙大） https://www.zhihu.com/column/c_1022809299793190912

## github 安全项目
 - https://github.com/crytic/awesome-ethereum-security
 - https://github.com/ConsenSys/smart-contract-best-practices

## poc & ctf
 -  https://github.com/OpenZeppelin/damn-vulnerable-defi
 -  https://github.com/blocksecteam/defi_poc

## 审计公司
 - 慢雾 （国内名气最大）
 - Blocksecteam
 - 知道创宇
 - 启明ADlab
 - Kudelski （目前最主流）
 - Quillhash


## 审计报告
 - https://github.com/thorchain/Resources/blob/master/Audits/THORChain-Kudelski-TSS-Audit-June2020.pdf
 - https://github.com/Quillhash/Audit_Reports


## 合约代码

### 借贷 & 质押挖矿

- https://github.com/compound-finance/compound-protocol
- https://yearn.finance/
- https://github.com/curvefi/curve-contract

### dex 去中心化交易所
- https://github.com/Uniswap/v1-contracts
- https://github.com/Uniswap/v3-core 新版
- https://github.com/sushiswap/sushiswap 出过洞，参考 defi_poc https://zhuanlan.zhihu.com/p/372058217

