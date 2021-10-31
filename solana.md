## 环境安装

- https://docs.microsoft.com/en-us/windows/dev-environment/rust/setup
- 安装 vsode rust
- 安装 rust-analyzer CodeLLDB 插件，如果报错缺少源码则运行 `rustup component add rust-src`

## solana 环境
 - 设置 devnet： `solana config set --url devnet`
 - 新建账户 `solana-keygen new`
 - 获取空投 `solana airdrop -k owner.json 10` 或者 `solana airdrop <address> 10`


## sol 概念
 - 从exmaple hello world 开始看 https://github.com/solana-labs/example-helloworld
 - 同步可以看开发者视频 https://www.bilibili.com/video/BV1ev41157bs/?spm_id_from=333.788.recommend_more_video.0

 - 涉及的概览在 https://docs.solana.com/developing/programming-model/overview 上
 - 和 ETH 合约主要区别有两点：
  -  1. instruction， instruction 类似 eth 合约函数，一个交易中可以调用多个 instruction，打包的 instruction 中有一个失败则交易失败，类似 mysql 的事务。
  -  2. account, eth 的数据存储在合约中，代码中是一个合约的全局变量。 solana 的数据存储在 account 中，account 隶属于某一个 program (合约). 一个合约可以有多个 account


