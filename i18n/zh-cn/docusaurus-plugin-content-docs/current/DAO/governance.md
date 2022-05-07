---
slug: /governance
---

# 🗳 治理过程

当前的治理流程包含以下部分:

- [Snapshot space](https://snapshot.org/#/nation3.eth): $veNATION持有者可以对提案进行投票。在不久的将来，公民（持有NFT国家护照的人）将能够提出治理方案并对其进行投票。
- [Aragon DAO](https://client.aragon.org/#/nation3): 实际持有资金者的DAO。这个DAO由$Ventation持有者管理。
- 提案委员会：一个由公民选举并由$Ventation持有人（未来由公民）批准的委员会，负责向Aragon DAO提交通过的快照投票，以便$Ventation持有人批准此类提案。

提案将经过以下步骤:

1. 作者将其发布为论坛帖子。
2. 作者在Snapshot上提出。
3. 公民投票（持续时间为48小时）。在公民护照推出之前，投票的是$veNATION持有人。
4. 如果获得批准，提案委员会的任何成员都会向 Aragon DAO提交提案。
5. $veNATION持有者批准（正常提案的期限为24小时，敏感提案的期限为一周）。

我们可以将这一体系视为两院制，公民是最积极的治理参与者，但需要与$veNATION持有者保持一致。激励措施是一致的，公民也需要锁仓$veNATION以保持公民身份。

这个治理过程旨在启动社区内的治理过程，但它不是最终方案。

## DAO的权限

这个DAO不仅拥有Aragon DAO的权限更拥有以下权限:
- 两种代理权 [Agent app instances](https://aragon.org/agent): 一是—名为基本代理权— 用于持有资金和控制非敏感行为，另一个— 名为代表治理($veNATION持有者的绝大多数)权—用于控制异常或敏感行为，如创建新的$NATION或对DAO本身进行重大更改。
- 两个投票应用实例：每个代理应用一个。第一个由$veNATION持有人管理，拥有简单多数票，另一个拥有绝对多数票（66%）和最低法定人数（20%）。后者用于决定敏感行动。

下面是权限结构的细分:
![](https://user-images.githubusercontent.com/718208/164224949-10b3c522-9016-4ad8-98e3-c214635237e4.png)
![](https://user-images.githubusercontent.com/718208/164223663-1781297a-a82d-4fc3-a9d1-8cb0b25bba60.png)

## 目前由DAO所管理的是什么

- 通过普通代理实例可知:
  - 它的财政部，由$NATION最初的大部分资金组成
  - [`MerkleDistributor`](https://etherscan.io/address/0xcab2B7614351649870e4DCC3490Ab692bf3beD60) 用于推特投放的智能合约
  - `PassportIssuer` 用来铸造和产出护照的智能合约
  - [`BoostedLiquidityRewards`](https://etherscan.io/address/0x4f1e79793fd5f5805b285c3f29379b8056a4476b) 用于分配流动性奖励的智能合约

- 通过代理（VeNATION绝大多数持有者）实例:
  - $NATION代币（DAO可以决定铸造时间表，或限制供应）
  - 获取它自己的投票参数和其他关键DAO参数

## 谁是最初的提案委员会成员

- [Luis Cuende](https://twitter.com/licuende): Nation3的核心贡献者,曾经是Aragon的创建者。
- [Carlos Juarez](https://twitter.com/0xPaella): Nation3的核心贡献者, 曾经是Guesser的创建者(最终被Gemini收购)。
- [Uxio Piñeiro](https://twitter.com/0xgallego): Nation3的核心贡献者, 智能合约工程师。
- [Anastasiya Belyaeva](https://twitter.com/anastasiya_vc): Nation3的核心贡献者, 曾经是Fabric Ventures的创建者。
