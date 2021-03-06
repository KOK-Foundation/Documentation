# KOK PLAY WHITE PAPER

**Version 0.3.0-0 (November 21, 2019)**

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/logo.png)

> Fair & Shared Digital Contents Ecosystem Enabled by Blockchain and AI

<!-- MarkdownTOC depth=4 autolink=true bracket=round list_bullets="-*+" -->
- [KOK PLAY WHITE PAPER](#kok-play-white-paper)
- [EXECUTIVE SUMMARY](#executive-summary)
- [KOK PLAY开发动机](#kok-play%e5%bc%80%e5%8f%91%e5%8a%a8%e6%9c%ba)
  - [社会性问题](#%e7%a4%be%e4%bc%9a%e6%80%a7%e9%97%ae%e9%a2%98)
  - [当前区块链瓶颈](#%e5%bd%93%e5%89%8d%e5%8c%ba%e5%9d%97%e9%93%be%e7%93%b6%e9%a2%88)
  - [网络问题](#%e7%bd%91%e7%bb%9c%e9%97%ae%e9%a2%98)
  - [管理制度问题](#%e7%ae%a1%e7%90%86%e5%88%b6%e5%ba%a6%e9%97%ae%e9%a2%98)
  - [软件问题](#%e8%bd%af%e4%bb%b6%e9%97%ae%e9%a2%98)
- [KOK平台的结构](#kok%e5%b9%b3%e5%8f%b0%e7%9a%84%e7%bb%93%e6%9e%84)
  - [区块链共识(BaaP)](#%e5%8c%ba%e5%9d%97%e9%93%be%e5%85%b1%e8%af%86baap)
  - [BP选择机制(DPoSS)](#bp%e9%80%89%e6%8b%a9%e6%9c%ba%e5%88%b6dposs)
  - [BP共识机制 (PPBFT)](#bp%e5%85%b1%e8%af%86%e6%9c%ba%e5%88%b6-ppbft)
  - [DApp开发及实施环境(AutoXML)](#dapp%e5%bc%80%e5%8f%91%e5%8f%8a%e5%ae%9e%e6%96%bd%e7%8e%af%e5%a2%83autoxml)
  - [分散式人工智能](#%e5%88%86%e6%95%a3%e5%bc%8f%e4%ba%ba%e5%b7%a5%e6%99%ba%e8%83%bd)
  - [开放式API](#%e5%bc%80%e6%94%be%e5%bc%8fapi)
  - [KOK DApp开发套件](#kok-dapp%e5%bc%80%e5%8f%91%e5%a5%97%e4%bb%b6)
- [KOK生态系统](#kok%e7%94%9f%e6%80%81%e7%b3%bb%e7%bb%9f)
  - [KOK DApp生态系统](#kok-dapp%e7%94%9f%e6%80%81%e7%b3%bb%e7%bb%9f)
    - [KOK媒体平台](#kok%e5%aa%92%e4%bd%93%e5%b9%b3%e5%8f%b0)
      - [i. 当前媒体平台的问题](#i-%e5%bd%93%e5%89%8d%e5%aa%92%e4%bd%93%e5%b9%b3%e5%8f%b0%e7%9a%84%e9%97%ae%e9%a2%98)
      - [ii. 区块链媒体平台](#ii-%e5%8c%ba%e5%9d%97%e9%93%be%e5%aa%92%e4%bd%93%e5%b9%b3%e5%8f%b0)
      - [iii. KOK媒体商品](#iii-kok%e5%aa%92%e4%bd%93%e5%95%86%e5%93%81)
    - [KOK游戏平台](#kok%e6%b8%b8%e6%88%8f%e5%b9%b3%e5%8f%b0)
    - [KOK购物平台](#kok%e8%b4%ad%e7%89%a9%e5%b9%b3%e5%8f%b0)
      - [个人交易(P2P)](#%e4%b8%aa%e4%ba%ba%e4%ba%a4%e6%98%93p2p)
      - [个人和企业之间的交易(B2C)](#%e4%b8%aa%e4%ba%ba%e5%92%8c%e4%bc%81%e4%b8%9a%e4%b9%8b%e9%97%b4%e7%9a%84%e4%ba%a4%e6%98%93b2c)
    - [KOK挖矿方式](#kok%e6%8c%96%e7%9f%bf%e6%96%b9%e5%bc%8f)
    - [KOK钱包](#kok%e9%92%b1%e5%8c%85)
    - [KOK代币的价值制定](#kok%e4%bb%a3%e5%b8%81%e7%9a%84%e4%bb%b7%e5%80%bc%e5%88%b6%e5%ae%9a)
    - [KOK 价值制定机制](#kok-%e4%bb%b7%e5%80%bc%e5%88%b6%e5%ae%9a%e6%9c%ba%e5%88%b6)
- [KOK平台的进化](#kok%e5%b9%b3%e5%8f%b0%e7%9a%84%e8%bf%9b%e5%8c%96)
  - [路线图](#%e8%b7%af%e7%ba%bf%e5%9b%be)
  - [代币发行](#%e4%bb%a3%e5%b8%81%e5%8f%91%e8%a1%8c)
    - [KOK代币的KOK硬币互换](#kok%e4%bb%a3%e5%b8%81%e7%9a%84kok%e7%a1%ac%e5%b8%81%e4%ba%92%e6%8d%a2)
- [KOK平台团队](#kok%e5%b9%b3%e5%8f%b0%e5%9b%a2%e9%98%9f)
  - [管理团队](#%e7%ae%a1%e7%90%86%e5%9b%a2%e9%98%9f)
- [区块链产业和KOK蓝图](#%e5%8c%ba%e5%9d%97%e9%93%be%e4%ba%a7%e4%b8%9a%e5%92%8ckok%e8%93%9d%e5%9b%be)
- [法律声明](#%e6%b3%95%e5%be%8b%e5%a3%b0%e6%98%8e)


* * *

# EXECUTIVE SUMMARY
2022年，全球文化内容市场收益预计达到60余亿人民币。市场预期， 到2021年，其中的数字内容占比将从2012年的33.5%，以每年高达20%的 增长率增长至53%。
过去，人们若要享受文化内容就必须去电影院或演唱会现场，但现在只需要一台手机就能畅快享受所 有内容。
得力于NETFLIX、YOUTUBE、GOOGLE PLAY STORE等数字内容平台的问世，数字内容市场急速增长。受益 于此，内容得以流通到世界各地。但随着全球化加剧，几个大型平台的垄断情况也越加严重。这导致平台的影响力大大地超越了内容提 供者的影响力。

最终，内容提供者即使支付给平台巨额手续费，也未必能获得机会展现其内容。这就陷入收益上的恶 性循环。更糟糕的是，随着平台在选择内容上的影响力日渐加大，内容会随着平台的发展性逐渐单一化， 市场被扭曲。当前，内容生态系统正走在衰退的路上。

而近年崛起的区块链技术通过其核心价值“去中心化”展现了构建民主体系的可能性。这种区块链技 术不会被集团或中央势力所控制，链上所有交易和活动皆公开透明，因而不存在伪造或作假的危险性。KOK 基金会注意到了区块链所展现的可能性，因此使用该技术开发了数字内容流通平台。

KOK PLAY是一款去中心化的数字内容平台，它结合了本公司拥有的AI及大数据技术与目前备受瞩目的 区块链技术。其开发目的是为了实现 “Fair， Share， Enabler” 此三大价值，希望能借此解决现有全 球平台的垄断化问题。在KOK PLAY里，所有创作者都能公平地使用平台资产(Fair)，共享价值与展望、 获得相应的公平收益(Share)，同时，创作者的创作自由也能得到保障(Enabler)。KOK PLAY将与所有 参与者一起打造最优质的平台!

* * *
  
# KOK PLAY开发动机

## 社会性问题

**• 中心化服务**

当前几乎所有平台都用中心化的模式创造收益。苹果商店和谷歌商店会收取付费APP获益的30%作为手 续费。除此之外，APP内道具收益的30%也需上缴给它们。在这种模式下，所有APP提供者都必须支付高额手 续费给中介平台。不仅如此，若要在平台上付费购买服务，就必须使用中心化金融机构所发行的银行卡才 能进行支付，这使得大规模没有银行账户的人完全无法使用该平台提供的服务。

**• 失衡的获利模式**

使用中心化服务的模式只会反复发生权利失衡的问题。以脸书、推特和Instagram为例，他们从股东、 职员和社区劳动等处获得利益后，再用这些利益设立数十亿美元规模的公司。产品收益归管理者，实际创 作内容的制作人却只能获得“成果”、“奖状”和“名誉”，这导致整个大环境都变得不愿意积极改善商 品品质。


## 当前区块链瓶颈

比特币最初的发明目的是为了让人们不使用政府机构发行的货币，以匿名的方式用比特币进行汇款。 出人意表，区块链的应用场景在2009年后急速增加。智能合约、DApp、分散式自律组织，全世界运动家都 想方设法地要将这些概念套入区块链的框架里。尝试过程理所当然遭遇到了困难。以太坊共同创立者维塔 利克· 布特林将他所遇到的问题都搜集了起来，主要有管理制度、运行速度、浪费、DApp使用性及采纳等 四个问题。要突破当前瓶颈就必须设想:如何打造一个可以同时解决这四个问题的去中心化区块链?

## 网络问题

**• 效率**

维塔利克· 布特林:“PoW每年浪费数十亿美元，这比诈骗和盗窃的总金额还多。是非常严重的问
题。” 现在的区块链项目，即使是最先进的也同样深受此问题困扰。也就是说，目前所有交易都是一件件处
理的。这问题并非只体现在工作量证明(PoW)区块链中，也同样出现在权益证明(PoS)区块链里。交易 以区块为单位被存储，一个区块只能由一个节点生产。在此结构下，交易和智能合约只能依序执行。这导 致区块链后端的网络将转变成超级电脑，从而夺走99.99%的计算能力。

## 管理制度问题

**• 基础设施的集中化**

维塔利克· 布特林:“比特大陆及其合作矿池现在共持有53%的比特币哈希算力。这可真是个严重的 问题啊!”这体现出了网络资源中心化的风险在于，即使只对少部分人进行支配、渗透或终止，也可能会 导致PoW网络遭受重大损失的严重后果。


**• 管理制度**

维塔利克· 布特林:“如果仔细思考过EOS管理制度为什么会失败的话，或许就会了解这代表着去中心 化自律组织(DAO)等区块链管理制度存在根本性缺陷。试想，有哪个去中心化自律组织能够对抗贿赂攻势 和金权政治呢?”
现有管理制度也有很多值得学习的优点，这些优点可通过现有的运行方式、框架和尝试习得。但也有 几点是我们必须从一开始就指出问题进行修正的。计算机科学家正在寻找最佳解决方案，让区块链免受恶 意攻击和夺取。就像美国宪法一样，强大的体系将会成为未来多变时代的基石。因此我们在设计平台时， 唯一考量的点就是:在数字货币中何谓公平支配?

## 软件问题

**• 实用性**

维塔利克· 布特林:“为什么仍然没有实用的大规模APP?” 
大部分区块链都已引入智能合约等可执行的独立体(entities)。如果使用新发明或简单的编程语言， 可能会减少代码的可信度和表现力。而智能合约又短又简单。区块链使用的语言和技术不允许开发丰富的 功能和强大的系统。数个智能合约的代码就可能超过一千个。但是，复杂的商务逻辑、丰富的内容制作、 连接多方用户的DApp，这些都可以在KOK平台实现!


**• 安保性**

维塔利克· 布特林:“为何么迄今为止仍然没有解决安保问题的良好方案?何时才能解决账户黑客和 被盗的问题?”
大部分区块链只提供可执行代码的编译器，没有装置测试、持续性统合、代码分析所需的道具，这导 致了只有简单性才能保护得了智能合约，让智能合约免受安保侵害。复杂的智能合约存在缺陷和弱点，关 于安保事故的报告也已被提出。如果为开发者提供更好的开发道具，就能避免巨额损失这类的安保事故。 因此可以说，KOK平台在构建具备丰富功能、高效率及优质生产环境的DApp上所做的努力是一项重要的创新。 我们找出了大部分区块链问题的解答。

* * *

# KOK平台的结构
KOK平台的DApp是一个服务群体。DApp就类似于一般网络服务 中的搜索引擎。

GOS-BP根据Group Theory的'对称结构特性'选定BP，此结构是通过参与主网的代表NODE来打造DApp生 态系统，这不仅有助于KOK平台的安全化，也能急速扩张KOK平台。「对称结构」会将相似的DApp结构内所 产生的交易数、节点分布程度、时间复杂度进行比较，再通过“结构化”检验相似性并进行分组。这种相 似性可归为一个大的Group。将Group内的相似结构最佳化就能克服区块链现有的局限。我们称此为GOS-BP (Group Of Symmetry - Block Producer)。


![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/gos-bp.png)

DApp服务群内有代表节点(Primary Node)，代表节点是指KOK平台的BP (区块生产节点、区块生产 者节点)。DApp服务群与代表节点连接后构成自身DApp服务生态系统。DApp服务生态系虽然类似于侧链， 但是并不具备DApp代币，它可连接并融合许多Off-Chain服务及DB，使其功能得以体现。奖励等代币经济中 所需的代币在获得KOK基金会分配的KOK后便可使用。

## 区块链共识(BaaP)
所谓新世代网络是指有价值且值得信赖的网络，若说现世代网络的代表是WWW (Worldwide Web)的话， KOK基金会预期WWBW将会超越WWW成为下一代具代表性的网络。然而现在区块链正陷入进退两难的地步。以太 坊创始人维塔利克· 布特林将此称为区块链Trilemma(三元悖论)。他认为安保、扩张性和去中心化这三个 区块链特性无法同时实现，最多只能实现两个。许多区块链正在努力解决三元悖论的问题，我们KOK平台也是。


很多观点都认为区块链是公共财产性技术、技术性Commodity，认为它是万维网上新生成的Economic Layer。经济合约行为和交易中不可缺少的信赖和根本价值能在Economic Layer，即区块链协议中提供保证。 像这样将区块链看做Economic Layer时，更容易生成DApp，Worldwide Web网络正朝着下一阶段的网络WWBW– World Wide区块链网络的方向发展。KOK平台作为这样的BaaP，使得众多DApp能在本平台上轻松生成。


为达成上述目标，KOK平台选择使用AutoXML技术，此技术可以将Worldwide Web Consortium所定义的数 据标准体现为全自动化引擎。AutoXML技术可以使区块链成为另一共识阶层，也使用数据标准传送Web内呈现 的双向数据。由AutoXML所创建的DApp会在Web内连接形成一个模式，这就是WWBW。


## BP选择机制(DPoSS)
区块生产者(Block Producer，下简称BP)是指受委托生产区块并决定主要政策的节点，每个DApp都具 备成为BD的资格。被选做BP的DApp商家会获得BP生产节点所产生的奖励。成为BP的方法和条件如下所示。


**1. BP选择方式**

- 选择对象:提供优质DApp服务的DApp。
- 选择方式:根据代币持有者的投票率和服务使用率决定优先顺序。 
- 获选BP将获得生产区块的奖励。


**2. BP资格**
 
- 为了成为BP获得奖励，DApp必须构建并运营节点服务。
- 以最小规格为准使用云服务时，构建服务每月需支付约$500的费用。
- 虽需支付费用，但若考量到区块生产的奖励，成为BP依然是相当值得的高收益投资。



## BP共识机制 (PPBFT)
初期组成KOK主网的BP有21个，每三个BP形成一个Region。


- 每个BP都有2个logic层，上层是服务layer，下层是负责Consensus的Communication Layer。 主网上线后，若DApp未正常启动或尚未准备好，此时代表DApp的BP就会以Dummy BP的身份，通过下 层的Communication Layer参与主网运行。
- 7个Region会考量全球通信网和DApp的分布情形，于主网上线前固定好。
- 早期主网生成时，Region会有固定指数BRI(Block Region Index)，BRI由0~6其中一个数字所 组成。
- BP具备固定指数BPI(Block Producer Index)。BPI在早期主网生成时就已固定，由0~20其中 一个数字所组成。
BP的指数会依据临近Region渐增。意即，Region0有BPI为0、7、14的BP，Region1有BPI为1、8、 15的BP。
- 生成部分区块所需的时间称为“区块生成区间(Block Production Period)”。在区间内， 会有一个BP负责生成第一个区块，该BP称为“Primary BP”。每个区间会生成24个区块。(区块生 成区间的区块数量可以通过Simulation和Testing进行调整。)

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/ppbft.png)

- Primary BP会在前一个区块生成区间被选定。选定方式为:将前一个区块生成区间所生成的第21 个区块的哈希值后4码进行module，并将module后得出的MOD 21函数定为结果值。MOD 21函数不 受Input的数值所影响，会自动设定为0以上20以下的整数值。此时得出的整数值即为下一个区块 生成区间的Primary BP的预定值。(将获选区块定为现在区间的第21个是为了顺利选定下一期 Primary BP，但在未来版本中此机制可能会有变化。)
- Primary BP的预定值加上1、2、3、4、5、6后，将各个数值代入MOD 21函数即会获得6个BPI， 这6个BPI为Primary BP的临近BP，是Region的“Lead BP”。Lead BP在区块生成区间会和Primary
BP一起在其隶属的Region里主导共识，并将共识结果通报给Primary BP。
- Primary BP会将自己初期生成的区块传给临近Region的Lead BP，Lead BP再将收集到的区块传给 其所属Region内的其他两个BP进行共识验证。此时的共识机制称为PBFT(Practical Byzantine Fault-Tolerance)。
- Lead BP将所在Region的共识结果传给Primary BP。此时的共识机制也是PBFT。 - 而KOK平台新共识机制为PPBFT(Parallel PBFT)，它整合了上述所有程序。

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/mod21.png)


## DApp开发及实施环境(AutoXML)

**• W3C和数据标准化**

W3C(Worldwide Web Consortium)在 1998年为了网络上接送的数据和其呈现而将数据呈现标准化。 标准化使用的Meta语言为XML(eXtensible Markup Language)。但由于XML的特性，程序若由编译器或人 类处理的话，较不易实现语法和技术。而AutoXML是XML的解决方案，它能将XML自动化，让XML更便于使用。

**• HTML vs XML**

Web对于区块链的应用服务DApp来说非常重要，因为DApp可以通过Web呈现给大众，信息也可以借此达 成流通扩散。在Web上呈现数据的方法有HTML和XML两种，HTML的目的在于向人们显示，属单方面的，而XML 在显示的同时还能交换数据，属双向性的。可以使用此属性编程制作DApp的智能合约。

**• 制作智能合约(Smart Contract Composition)**

智能合约的制作方式并非以类似于Solidity的基础语言进行编程，是以Drag-and-drop形式制作 (Composition)。


## 分散式人工智能
- KOK平台广泛引入人工智能。
- 首先，DApp使用适合该生态系统的AI，提供媒体策展等。
- 第二，BP使用分散式人工智能与相邻BP合作，并共同促进KOK平台的强健性与负载平衡。
- 第三，KOK钱包中装载了AI功能，可执行个人数据保险箱的功能，并通过分析适当的数据创造经济收益。

## 开放式API
KOK平台的DApp可以看作是一个服务集体，类似于过去网络服务中的搜寻引擎。DApp服务群内有代表节 点(Primary Node)，代表节点是指KOK平台的BP (区块生产节点、区块生产者节点)。DApp服务生态系 统即以这些代表节点为中心建构而成。


## KOK DApp开发套件
为了开发KOK平台的DApp，KOK基金会准备了KOK DApp Development Kit (KDDK)。KDDK提供开发、测试 和启动DApp时所需的所有工具和环境。

* * *

# KOK生态系统
KOK生态系统由三大部分组成，这种设计有利于平台的连接和进化。

**• KOK主网**

由依据GOS-BP概念创建而成的BP组成共识网络。KOK主网和KOK生态系统的核心数字货币是KOK币。

**• KOK DApp**

DApp拥有代表自己的一个BP，此BP负责管理该DApp的Sub生态系统，即DApp生态系统。 DApp是提供各种数字内容的综合型内容生态系统。虽然DApp生态系统主要使用KOK主网提供的KOK 币，但在特殊情况下可以设计自主DApp币，此时自主DApp币与KOK币的交换机制将随后公告。

**• KOK Play钱包**

KOK Play钱包让所有KOK使用者(BP组成的主网、所有参与主网与DApp的使用者) 都能分享公平的价值。KOK Play钱包也能与DApp连接，通过钱包购买心仪的内容。

## KOK DApp生态系统
KOK平台是一款提供多样内容的综合性平台。KOK钱包内可以享用各种内容。KOK生态系统大致由 “KOK媒体平台”、“KOK游戏平台”和 “KOK购物平台”等三个主题所构成。

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/kok_dapp_ecosystem.png)

三个平台都致力于解决当前服务的问题，通过使用区块链技术，制定一个更加透明且进步的未来平台 的标准。

KOK平台使用Economic Layer区块链创建WWBW(World Wide Blockchain Web)。KOK平台的经济结 构(Token Economy)是借由创建众多DApp获取收益。

### KOK媒体平台
KOK基金会不仅致力于改善YouTube、Facebook、Netflix、腾讯视频等当前主流媒体中存在的问题，还 积极引入区块链技术，以打造一款透明的区块链基础媒体视频平台。

#### i. 当前媒体平台的问题
当前媒体平台存在“广告费推定”、“收益分配”和“个人信息保护”等问题。
Youtube平台用户每日收看总时数平均超过10亿小时，但广告商和平台管理团队的利害关系却极度不平 衡。内容创建者(Contents Creators)和平台公司间的不透明收益分配，以及Facebook信息泄漏事件等个 人信息数据的盗用及黑客问题都是近期浮上台面的热门议题，这些问题都是中心化系统中难以解决的问题。

此外，强制收看广告、为提高创作者收益而故意填写评论(Abusing)等问题也随之而来。只有解决这 些问题，才能减少媒体平台的经济损失。

#### ii. 区块链媒体平台

**(1) 解决广告商与平台之间的问题**

广告商期望广告能在目标族群观看的频道内登载，然而事实却是由于当前平台的机制，广告总在View bot和不健全的内容中登载，对此广告商在“目标设定”和“广告效率”方面甚感不满，也逐渐减少广告费 的支出。内容创造者则因此收益减少，对中心化平台的不满也日益增加。

**• 消除‘View bot’滥用**

区别一般用户和“View bot”的过程相当复杂。KOK生态系统中，用户能用KOK币自由进行消费。因此
KOK基金会制定KOK币的消费条件和KOK实际用户的选择标准，借此区分“View bot”和实际用户。

KOK基金会通过“完成实名认证的KOK币挖矿”、“一定水平的KOK币消费”和“用户钱包活跃性”等设 备区分实际用户和“View bot”。除了媒体之外，KOK平台作为一个具备游戏、音乐服务、电子商务等多元 内容的平台，平台内的支付均使用KOK币，因此并不难区分实际用户和“ View bot”。

**• 改善目标广告及广告效率**

区块链上不可能进行假评分和假评论。在没有BOT滥用的状态下所撰写的的评分能成为强大的武器。广 告商在KOK内容平台内通过评分区分高质量频道及视频，借此以观众提供的数据为基础进行有效的目标广告 投放。广告商在市场购买KOK币，购买的KOK币再重新消费在平台、用户和创作者身上，通过这种模式达成 KOK币生态系统的良性循环。

**•  频道及视频间的竞争力**

为了抑制不恰当的频道竞争力，KOK平台用KOK币来评价频道。用数字货币绑定评分也有助于激活整个 生态系统。但若仔细观察那些已在去中心化系统内导入此评价系统的先例的话，就会发现用户总是会为了 得到巨额奖励而刻意提高相互间的评分的情况，因而产生用户行为违背平台宗旨的问题。

若要被认定为一般用户，Abusing Bot就必须消费KOK钱包内的KOK币，并于特定时间在钱包生态系统 “活动”。这种设置能有效降低Abusing Bot的经济附加价值，并限制Abusing Bot的滥用。KOK平台用KOK 币阻断Abusing用户，从而构建频道的订阅者及视频评分体系。观看用户可以消费KOK对视频进行评价。持续进行评价的用户可以提供其“观看数据”给平台，借此获 得高于其消费的KOK币(进行评价和订阅)的奖励。

频道“订阅(Subscribe)”通过KOK币挖矿进行，KOK平台对总挖矿数量设立限制，借此增强拥有大量 订阅者频道的影响力。根据频道的挖矿总数提供奖励给频道创作者，借此选择并量产优质的频道。

**(2) 创建者与平台之间的问题**

当前知名视频平台的最大争议就是内容创作者获得收益的“支付过程”，然而如果应用区块链技术的 话，就能解决此问题。在当前平台中，由于“支付时间”(获得视频收益所费时间)、“透明支付”(广 告费)、“算法政策的修改”(收益获取相关)等问题，创作者与平台间产生了相当严重的摩擦。

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/pop.png)

POP(Proof of Participation)是参与度证明方式，它通过以下方式解决问题。 

1. 特定 N 小时内的观看时间
2. 视频内广告点击数
3. 视频评论数


KOK媒体平台的算法是计算内容的所有相互作用，将每个用户的视频观看数据储存在区块链里，用透明 公开的方式支付费用给内容提供者。这些费用基本上与收看时间成正比，辅以内容评价算法精密计算后进 行支付。


**(3) 用户与平台之间的问题**

YouTube与NETFLIX等媒体相继问世，个人数据也开始成为重要的资产。目前Facebook与YouTube的最大 争议是，个人数据不是通过奖励的方式返还给用户，而是被平台私有化。

尤其是因为近期震惊全球的Facebook个人信息泄露事件，身份数据加密化更理所当然地被认为是平台 必备要素。在KOK平台，个人数据被区块链加密后储存，广告商所需的数据(个人喜好视频类型、观看年龄 等)在得到用户同意后才会被收集，同时作为奖励，平台会发放KOK币给提供数据的用户。


#### iii. KOK媒体商品

在KOK平台上，用户除了可以上传并共享视频之外，还可以提供自己的媒体商品。该媒体商品将KOK自 身已经具有效益性并向市场公开的音乐、电视剧、综艺、电影、演出等上传至KOK平台，并与全世界共享。

平台旨在以在全世界范围内大受欢迎的K-POP(Korean Popular Music)为中心介绍大众音乐，并将可 以收听、下载的韩国代表音乐平台和KOK PLAY平台联动，提供音乐服务。

除K-POP以外，KOK平台还提供韩流代表电视剧，并以KOK PLAY原创综艺为首，提供各种频道的代表性 综艺。此外KOK PLAY平台也提供各种题材的电影。
举行代表K-POP的艺人演出及海外艺人演出，从而在销售演出门票的同时，也在KOK PLAY平台提供演出 实况转播服务。

**•  网红系统**

KOK平台支援网红在KOK媒体平台内的活动。在文化产业和电子商务市场中具有影响力和潜力的网红会 出演KOK平台各媒体内容，吸引用户关注。网红提供内容给用户，用户可以通过打赏KOK币来表达他对网红 的喜爱。广告商也可以通过KOK平台邀请网红为他们做广告，并用KOK币支付广告费。这种平台内部的广告 合约可以提升KOK币市价，也可以促进KOK币的交易活跃性。

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/influencder_system.png)

节点间的交易用奖励代币形成区块，在平台内完成交易。KOK平台会公开交易数据，借此分析广告商、 网红和顾客间奖励代币的流向，并用代币分析数据。

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/kok_platform.png)


### KOK游戏平台
**• 当前游戏产业的问题**

游戏开发者由于庞大的游戏外部营销费用(如谷歌Play、苹果商店等平台手续费)支出，正面临巨大 的困难。为了制作好玩的游戏，中小型游戏公司在研究游戏上就必须支付相当巨额的费用，若再算上这些 外部营销费用的话，着实是难以承受的负担。高额外部营销费用不仅导致游戏开发投资费用缩减，也是游 戏品质下降的原因之一。

用公平的方式经营游戏能让玩家更加热爱游戏。一直以来，玩家若要获得游戏内的装备，会购买 “数字资产Gacha”等道具，但同时他们也对其随机性存有疑虑。虽然要获得好装备就必须投入时间和金 钱，但这其中的任何数据都不对外公开，玩家难免会对此存有合理性的疑虑。

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/game_platform.png)

玩家对于游戏装备的所有权也会因为游戏供应商的服务条款或服务障碍等理由而丧失。游戏的忠实玩 家无法完整拥有游戏内部装备的问题需要全球游戏市场共同解决。因此综上所言，当前游戏存在成本问题 和游戏内部的信赖性问题。KOK平台的KOK游戏平台将用区块链技术来解决这些问题。

KOK游戏平台是一款可以使用KOK币支付的全球性游戏平台。开发者无需向平台支付当前支付给谷 歌Play、苹果App Store等接近30%的手续费，而是通过更加低廉的手续费政策减轻游戏开发者的负担。 还运用人工智能(AI)掌握平台用户的需求，并向合适的用户实施目标广告。

此外，KOK平台还提供开放数据，以便于外部开发者制作高质量的游戏。提供API手册、直接性工程支 持，支援开发以区块链为基础的游戏。游戏内部“获取数字资产”的概由KOK平台、游戏玩家和游戏运营商 参与随机数的生成，并以智能合约(Smart contract)为基础实现数字资产交易，透明地公开在区块链上。

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/game_process.png)

**• 开放式API**

平台通过公共API托管智能合约，使用XML-RPC协议体现与KOK钱包内代币的智能合约。可以通过智能合 约交换工具。发生游戏内的工具交换时，通过注册表对智能合约进行注册后，该工具在区块链上向所有用 户公开。API是为了管理程序，以关于智能合约的网页、手机为基础而开发的。

**• KOK钱包内的游戏平台**

基于区块链的游戏一般在“KOK钱包”内部提供服务。KOK平台的用户钱包和基于KOK的游戏通过API发 出交易请求，交易时KOK代币在钱包之间移动。产生交易时向用户标明与交易相关的信息，可以轻松接收或 拒绝，使区块链交易更加便利。

### KOK购物平台

正如以太坊的创始人维塔利克· 布特林所提到的，我们关于区块链需要弄清楚的是，区块链不是证明 有用性(Value)存在的手段，更恰当的来说是对不存在进行证明。例如，交易名牌产品并利用区块链证明 该交易存在时，虽然可以对交易进行证明，但是无法证明交易的名牌产品实际上是否为名牌产品。

如果区块链在对于存在的证明有困难，那么我们需要值得信赖的来证明存在的机构，需要通过值得信 赖的机构来对存在进行证明的装置。


块链意味着没有特定管理者或主人的P2P方式的个人间交易系统。区块链技术与现有的P2P形式的下 载方式类似，把本人进行过何种交易的证明内容储存在全球性分散的计算机中， 从而证明该交易内容。


正如前文所述，这种区块链虽然可以对不存在进行证明，但是对于存在的证明很难，因此需要和“值 得信赖的机构”或“值得信赖的人”进行交易。比起储存在分散化账本，这种值得信赖的机构或人需要是 政府进行保障或者另外的监督机构和保证机构。

KOK平台对与KOK财团和另外的监督机构(或保证机构)进行交易的财物或商品进行保证，对特定财物 或服务也支持个人之间的交易(P2P)以及个人和企业的交易(P2P)。
 

#### 个人交易(P2P)
个人和个人之间的财物或商品交易应该最先解决的问题是防止买家和卖家的欺诈。这个部分以多重签 名托管(Multisignature Escrow)形式解决。买家在交之前将“KOK代币”或其他数字货币(比如 ‘USDT’)放入信托账户，进入此账户的数字货币可以在3名人员中2名人员的同意下进行提取。一般来说， 虽然是在买家和卖家2人的同意下完成交易，但是经过特定时间后且买家没有特别提出异议的情况下也可以 取款。

但是卖家和买家之间发生纠纷时，第3方将介入并处理纠纷。卖家和买家在协商下通过社区内的判断和 评分筛选“纠纷调解人”，并提议交易仲裁者进行参与。这种系统是为了构建不带有中介者的去中心化网 络。

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/p2p.png)

**• 纠纷调解人**

在KOK平台内，任何人都可以成为“纠纷调解人”。“纠纷调解人” 可以在社区内活动并获得选拔的 机会，评分根据纠纷处理之后的处理手续费上涨，在纠纷中失败的买家或卖家可以再次请求KOK平台进行纠 纷调解，并请求终止交易。在KOK平台上对纠纷提出异议时，要承担附加手续费并可以向平台请求追加判决。 KOK平台随机选出社区内的“陪审团”在内部进行解决，或者在该国内存在法律问题时，根据该国的法律终 止相应交易，“国际法”上存在问题时则根据国际法终止相应交易。

**• 陪审团**

通过向KOK内部传输改变随机生成的哈希值，从而创造陪审团的公平筛选过程，在社区内活动的人员中 评分较高的“纠纷调解人”中随机选择100名构成陪审团。为了防止伪造，将改变随机哈希值的过程使随机 值的结果完全透明且可以验证，展现出公平结果的导出过程，并形成利害当事人之间的信赖。根据超过半 数的意见解决调停，超过半数不同意时，将反复陪审团的筛选及纠纷调解过程，重复相应作业直到超过半 数同意为止。

**• 纠纷调解人及陪审团奖励**

纠纷调解人及陪审团在解决纠纷时，将获得与销售额成特定比例的奖励。奖励通过KOK代币获得，并使 “KOK购物”平台社区内的评分增加。在今后发生追加纠纷时，测定的评分可以使其被筛选为纠纷调解人的 概率增加，并能够大大提高纠纷调解累计收益。

#### 个人和企业之间的交易(B2C)
个人和企业之间交易(B2C)时，经过验证的多数合作伙伴(品牌)的财物及服务将在KOK钱包内提供。 KOK钱包内的财物及服务将成为KOK平台生体系统向全世界进行宣传的机会窗口，KOK提供的韩流内容及商品 将为KOK平台带来巨大的营销效果。

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/b2c.png)

为了扩张KOK平台的生态系统和提高服务质量，KOK内的代表节点 通过多数表决选择可以为KOK购物平 台提供财物及服务的品牌。通过验证的品牌承诺保证所销售财物的品质，将证明该交易的transaction(TX) 留在交易对方的钱包，并以相应哈希值为基础记录交易完成。拥有关于交易的证明的买家能够以相应交易 为基础请求对质量进行保证，没有交易的第3方提出质量保证请求时则不会保证质量。

**• 消费者的大数据储存及应用**

综合消费者根据数据提供设定的个人信息、消费者的搜索数据和消费者的消费模式等相关数据，并上 传至KOK平台内部用户大数据服务器。上传至大数据服务器的用户消费数据累积，成为生态系统中用户大数 据形成的基础，在分析并理解线上购物活动模式时用作宝贵的信息。

消费者向KOK平台生态系统提供消费者的信息，是对形成KOK平台的价值做出贡献的行为，因此消费者 在KOK平台内获得一定的奖励。并非消费者单方面向购物中心和特定品牌提供数据，而是以提供的数据为基 础获得相符的数据。

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/app_data_blockchain.png)

**• 消费者(用户)奖励**

消费者的数据通过各种方式被运用于线上购物。消费者可以向KOK购物商城或品牌提供数据，并获得 KOK代币奖励。此外，如果接收相应广告也可以得到KOK代币作为奖励。


KOK购物商城内的品牌在市场购买KOK代币并支付给KOK平台和消费者，从而获得关于目标顾客的数据。 以这些信息为基础向平台支付KOK代币，有效实施目标广告。


KOK购物商城在收集数据的同时奖励KOK代币，并将数据提供给KOK购物商城内的品牌。还在实施目标广 告的同时利用KOK代币进行结算，为KOK代币的价值上升作出贡献。


### KOK挖矿方式

KOK主网追求的“DPOSS(Delegated Proof of Stake & Service)” 解决了当前 POS方式和DPOS的问题。 单纯POS方式的缺点是个人收益率较低，在以POS为基础的主节点方式的挖掘形式下，个人为了形成节点必须 拥有相当多的代币。大部分利益归于少数几个通过暗中勾结来制造节点的利益团体，也由于此管理上的问题 而遭受批评。

在“DPOSS”中，BP在提供优质服务的DApp中选定。在当前投票方式的同时，BP选择将根据DApp的服务激 活程度决定，并使用以下测定方式。

1. 投票
2. DApp使用率 
3. DApp销售额

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/mining.png)

BP(区块程序)的选择根据KOK代币持有者的“投票”、“DApp利用率”和DApp销售额决定排名。选定的 BP可以获得关于区块生成的奖励，是根据服务的人气产生额外收益的方式，因此DApp会努力获得KOK用户的投 票。不仅是投票，还通过测定服务利用率的方式有效解决DPOS的问题，即暗中勾结问题。

KOK区块链解决了当前主节点方式的问题。KOK代币持有者选择的BP起到主节点的作用，进行投票时所使 用的代币不再归自己的钱包所有，代币委托给投票的主节点BP。随着时间流逝，可以根据主节点份额获得区 块奖励，将按照投给投票者的票的比例进行分配。

不仅如此，KOK平台还提供额外奖励。KOK平台向将代币委托给主节点的代币持有者提供额外奖励。在KOK 平台内产生的部分收益将回馈给KOK平台，回馈的金额与销售额成比例测定，奖励给委托代币的用户。KOK代 币持有者在使用KOK平台的同时，还以各种方式挖掘KOK代币。

### KOK钱包
![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/kok_wallet.png)

除了基本的游戏、媒体、购物等主要内容之外，KOK钱包为了KOK生态系统的发展及稳定化还会提供几种追加功能。

1. 挖矿及投票功能
2. KOK租赁功能(P2P)
3. KOK投资功能(P2P)


KOK钱包提供的KOK挖矿功能，是一种向自己选择的BP挖矿代币的结构。除了挖矿KOK代币的情况下产生的 区块生成收益之外，对于BP提供的DApp中产生的销售额也将分配到部分销售收益。

为了打造KOK代币的积极价值，KOK钱包将KOK代币以P2P租赁方式出借给KOK代币用户。提供“KOK租赁功 能”和“KOK投资功能”，从而使投资者能够稳定拥有并消费KOK代币。

KOK代币的租赁可以通过在KOK价格上涨时以高价出售，归还相当于租借时挖矿资产“USDT”的金额的 方式进行交易。相反KOK价格下跌时必须以低价出售，并将相当于租借时资产的金额归还给出借者。

另一方面在使用“KOK投资功能”时，可以获得相当于投资金额的收益。这种情况下如果KOK代币下 跌，可以领回相当于最初投资时的USDT，因此会另外产生相当于下跌部分的利润。相反如果KOK代币上涨， 则无法得到关于KOK代币价格上升部分的收益。

KOK代币上涨时，可以利用“KOK租赁功能”高价出售，以获取收益。相反在使用“KOK投资功能”时， 虽然KOK代币价格上涨时会产生收益，但是无法得到关于价格上升部分的收益。相反，由于是相对于本金 收取利息的结构，因此可以进行稳定投资。

初期KOK代币的流通量是通过挖矿或使用“KOK投资功能”，利用获得的收益慢慢流通的结构。使用 “KOK租赁功能”时必须用KOK代币支付费用，因此初期在使用“KOK租赁功能”方面存在限制。

**• 安保**

提供可以利用基于面部或指纹等人体认证的KYC登陆功能，且在没有个人密钥管理的情况下也能简便 使用的KOK钱包服务。


**• P2P Transactions**

初期的KOK钱包之间并不支持P2P直接交易。在KOK主网和KOK专用钱包上市，KOK代币被交换为KOK币的 Milestone 4 (2020年 9月)时即可实现。

**• KOK钱包和DAppDApp的连动**

KOK钱包在KOK DApp中以应用内形式运用， 也通过KOK DApp的终端节点形式使用。支持通过手机认证 进行的实名认证水平的KYC体现及AML，也支持DApp开发。

### KOK代币的价值制定
KOK代币的价值在生态系统内通过各种各样的方式决定，以几种核心要素作为基础。

**(1) 平台销售额**

KOK平台直接提供的平台内各项内容(游戏、音乐、视频等)产生的销售额(广告收益、流媒体服务 收益等)从广告商或平台服务消费者(用户)处获得KOK代币。广告商或消费者必须在市场购买KOK代币， 这会影响价值上涨。平台收益的一部分会重新奖励给持有人。


**(2) DApp销售额**

广告主和DApp消费者在市场买入代币即完成消费。虽然消费的一部分会再次以奖励的方式归还给代
币持有者，但消费依然有助于币值的上升。

**(3) 平台提供收益**

作为KOK平台将DApp服务提供给当前用户的补偿，DApp内的部分销售额将返还给KOK平台。这里产生的
销售额中的一部分会奖励给代币持有者。

**(4) KOK投资者的增加**

一般的数字货币被用作基于去中心化的价值储存的手段。这也使得大部分硬币在市场形成了最起码的 价值。在此基础上，如果许多投资者对KOK代币感兴趣并投资的话，则会被用作相对稳定的价值储存手段， 并影响价值上涨。


### KOK 价值制定机制

KOK代币的价值决定因素分为在数值上可测定的部分和不可测定的部分。

“平台销售收益”和将平台提供给DApp而获得的“平台提供收益”可以数值化。此处产生的总销售额 (销售额+提供收益) 中，奖励给代币持有者的量调整到50%以下，剩余50%以上的收益将用于KOK代币的市 场价值上涨，从而对KOK代币的价值产生积极肯定的影响。

除此之外，决定KOK代币价值的“KOK代币投资者增加”或“平台服务使用费”等很难在数值上进行计 算的部分也同样影响市场价值，为KOK代币价值上涨作出贡献。

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/kok_value.png)

 在KOK平台使用“挖矿”和“KOK投资功能”时，会分别产生奖励收益和借贷收益。使用“挖矿”和 “KOK投资功能”时，代币存在于钱包中，且不向外流通，这将被用作显著减少KOK代币出售的装置。

使用KOK平台的用户持续增加时，销售额也将成比例增加。一般的投资者属于“规避风险者”，因此 会努力在钱包内获得“奖励收益”和“借贷收益”。市场上未发生代币价格上涨超过“挖矿收益(奖励收 益+借贷收益)”时，KOK代币的市场内出售将受到限制。

市场价格上涨率高于“挖矿收益”时，投资者会在市场内以价格评断KOK币，此举能活跃市场内的KOK 币交易。另一方面，若市场价格上涨率低于“挖矿收益”，在市场买入KOK币后到钱包使用挖矿和投资功 能会比较有利。在这种情况下，市场内KOK币的流通量会降低，这种机制能成功降低市场卖出率。通过使 用“挖矿收益”提高KOK币市场价值的机制，KOK币的市价得以稳定维持。

* * *

# KOK平台的进化
## 路线图
KOK生态系统会将已存在的数字内容模型转为DApp形式后存储至区块链。
 
![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/kok_roadmap.png)

## 代币发行
KOK的总发行量为50亿个，永不增发。根据初期5年发行计划，前五年将挖掘总量的30%，即15亿个。

主网上线前的代币将通过KOK平台和KOK平台搭载的DApp共识分配给平台用户。也可能通过初期平台 用户提供的信息所产生的奖励，或通过初期在KOK平台及DApp中挖矿的方式分配KOK币。

主网上线后，生产区块的BP将得到奖励，进行BP投票和挖矿的代币持有者则根据BP的政策获得奖励。

将总发行量设定为50亿个是为了保有足够的奖励给BP。实际流通量将在初期5年过后，也就是发行 15亿个之后逐渐减少。

如前所述，KOK平台的部分销售额将作为挖矿奖励发放给平台用户，而另一部分将被使用或销毁， 借此提高KOK币的价值。KOK平台会销毁持续产生的一部分KOK币，为提高KOK币的价值作出贡献。另一方 面，KOK平台也必须每年提供一部分KOK币给BP作为生产区块的奖励。

KOK平台和BP在共识下决定生产区块的奖励。该年度的区块奖励不能超过前一年度销毁的代币数量。 KOK平台也掌握用户的挖矿情况，上一年的平均挖矿数量越多，该年度的区块奖励数量就越接近前一年 度已销毁代币的数量。

KOK生态系统总合是指KOK平台和KOK平台初期生态系统(媒体平台、游戏平台、购物平台)。对初 期生态系统作出贡献的Dapp和节点将会依据初期发展计划获得KOK代币。

分配的代币将按照使用该DApp的用户数和挖矿的比例重新分配。分配将根据DApp的政策，通过不同 的奖励结构在不同时间进行。
 

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/token.png)

### KOK代币的KOK硬币互换
在KOK平台的主网准备完毕，且KOK生态系统的基础硬币准备好时(Milestone 5)，在初期以ERC20形 式发行的KOK代币将可用1:1的比例兑换为KOK硬币。

* * *

# KOK平台团队
KOK基金会负责开发运营KOK PLAY。 (https://kok-play.io/ )

## 管理团队

**• CEO 黄东燮**

黄东燮CEO毕业于延世大学媒体宣传研究生院广告宣传学系，为THE GROOVE 娱乐公司创始人兼总代表、GOM Picture共同代表，以及韩国演艺制作协会理事。

他是韩国知名演艺制作人，专门制作唱片、电视剧、电影、综艺等各式各 样的娱乐内容。他曾制作Free Style、MC haNsAi、Bigmama Soul、Wanted金载 锡、朴慧京、Hanbyul等歌手的专辑，以及MBC《最佳爱情》、MBC《一号国道》、 KBS《王家一家人》、JTBC《吧嗒吧嗒》、SBS《Remember》、KBS《Good Doctor》、MBN《心动警报》等电视剧OST，此外还参与了《德九》、《真凶》、 《第8天的夜晚》等电影的制作。

黄东燮CEO曾于2016年韩国内容振兴院颁奖典礼荣获“大众艺术文化产业发展部门功勋奖”，于2014年韩 国内容颁奖典礼荣获文化交流贡献部门长官表扬，于21届大韩民国文化艺术颁奖典礼荣获“电视剧OST制作人 奖”，也曾获“2014年韩国演艺制作人协会大众文化产业发展贡献部门功勋奖”等大奖。

**• CTO 崔永奎**

崔永奎CTO1980年毕业于首尔大学原子核工程科，目前担任ICObench评价委 员、Crypto Valley Lab，Inc创业者兼CEO、延世大学工科学院兼任教授。

崔永奎CTO多年来在各种国际性区块链课题中担当顾问，其中代表性课题有 Q DAO、EdenChain、GBC Korea(UCX)、EOS Chrome(Ledgis)、EDC区块链、 ACCBY链、ID&D(ED币)、Boltt协议等。同时，他还在区块链领域相关月刊 《区块链TODAY》中担任编辑委员。

他担任4世代数字货币与作为DApp平台的Color Platform的Co-Founder/CTO/技术总监。崔永奎CTO毕业于 美国北卡罗莱纳州立大学，隶属软件工程科的系统软件系，并在BMC Software圣何塞实验室、三星电子技术 总监SW研究所、NVIDA韩国研究所、SK Hynix美国先行研究所、3Ksoftware USA、成均馆大学软件工程科等机 构任职，任职期间其理论与实践以及技术经营能力备受赞誉，在区块链领域中被称为概念设计与结构设计、 Revised与Reverse ICO、线上与线下的统合专家。

此外，崔永奎CTO还参与了Linux等开源软件的生态系统扩散课题，并担任韩国区块链产业振兴协会 (KBIPA)创始理事。崔永奎CTO目前还兼任负责Crypto-Finance与Cyber security关联业务的3KFinance的 CSO。 (https://www.linkedin.com/in/young-choe-8033684/ )
 
**• COO 姜智源**

姜智源COO毕业于汉阳大学国际观光研究生院娱乐内容学系，是Nexon子公 司“SuperAcid”的代表理事兼共同创始人，现任THE GROOVE娱乐公司COO。

目前正以手游开发者的身份活跃于多元游戏制作，其代表作是以韩国知名 漫画“三国战斗记”为背景制作而成的同名手游《三国战斗记》，本款游戏版 权已授予SmileGate和北京触控科技。

他开发的动作类RPG手游《Magia:Charma Saga》获得Nexon700余万美金的 投资，现已于全球130多国正式上线。
姜COO曾于2013年至2014年担任韩国内容振兴院外部编辑委员，撰写CONTENTS白书，曾任翰林大学研究生 院兼任教授。
(https://www.linkedin.com/in/g1-kang-6b134567/)

**• CSO 朴星俊**

朴星俊CSO负责KOK基金会的平台设计及战略制定工作。2010年，朴CSO自韩 国首尔大学经营学系毕业，他曾监制《地下城与勇士》(Nexon游戏公司出品， 曾登顶多个游戏榜)、《暴能特区》等知名游戏，也曾负责Hyperconnect公司 旗下APP——《AZAR》的付费模式制定及游戏运营，该APP在全球范围内的使用 人数超过两亿。

此外，他创立游戏开发工作室“Netker inc”，并兼任工作室代表，亲自 开发线上游戏《Versus》和手游《Moebius》，此工作室曾收到SmileGate等多 家公司的投资共计300余万美金。

* * *

# 区块链产业和KOK蓝图

**'工业4.0&创造新契机首尔2019'**

KOK基金会于2019年9月30日在首尔龙山区Dragon City酒店举行“工业4.0&创造新契机首尔2019”论坛。 本次论坛旨在介绍第四次工业革命时期成功融合既有产业后重生的优秀企业案例，同时公开宣布KOK平台的 发展策略及蓝图。

论坛上半场，韩国朝野国会议员及各产业代表分享了他们对未来产业的想法，下半场则聚焦于介绍用 第四次工业革命创新技术打造而成的KOK平台。

* * *

#  法律声明
KOK币不具备证券和股份的法律性质。因此KOK币不会赋予任何关于分红及利益的权利。KOK币销售完毕 后，不可退换。KOK币不具备股份的性质，因此并不保证，拥有KOK币就具备参与KOK基金会会议的权利。因 此，无法将KOK币用于投机或投资目的。本白皮书不具备法律约束力，不构成任何合约关系。

本白皮书内容虽然努力提供准确的信息，但公布的信息可能会更改，不对其准确性及完整性负有任何 责任。投资者需自行对相关信息及规定进行精密调查，决定项目投资，且投资者本人必须熟知管辖国家的 相关法律。

取得和储藏KOK币可能包含各种风险。此风险包括KOK基金会上市区块链，无法提高 其技术或者无法提 供以上提及的服务。因此获取KOK币之前，希望所有用户及投资者注意仔细考虑获取KOK币引发的风险、价 格和优惠等。必要时，请各位听取此方面相关专家的意见。不能理解或无法接受此风险和条款中明示的其 他风险的购买者，建议不要购买KOK币。

由KOK基金会(和公司)制定的白皮书旨在向KOK币(和代币)的潜在购买者传达关于推出所提案硬币 的相关信息。白皮书的信息可能不完备，且不含有任何合约关系的要素。此白皮书的正常目的在于为潜在 持有者提供合理信息。本白皮书的任何内容都不带有建议提案或投资劝导的形式，也不包含为购买特定管 辖权内的证券而进行的建议或关于此的任何形式的委托。此外，此白皮书的任何内容都不构成广告或营销 刊物，与提供或购买属于管辖权内的有价证券也毫无关联。
本白皮书仅旨在对KOK项目(技术方案)进行说明，且不包含任何意见或承诺，在此项目的实现可能性 和合理性及竞争力层面，我们不保证最终目标将满足阁下的期待。KOK币购买者必须同意已对本白皮书及法 律告知充分理解，并承诺遵守购买者居住地的法律，尤其是防止洗钱、恐怖袭击等的相关法律，且已经充 分体验和理解数字货币及区块链技术。本白皮书以韩语及其他语言发行，解释上产生冲突时韩语版本优先。