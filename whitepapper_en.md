# KOK PLAY WHITE PAPER

**Version 0.3.0-0 (November 21, 2019)**

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/logo.png)

> Fair & Shared Digital Contents Ecosystem Enabled by Blockchain and AI

<!-- MarkdownTOC depth=4 autolink=true bracket=round list_bullets="-*+" -->
- [KOK PLAY WHITE PAPER](#kok-play-white-paper)
- [EXECUTIVE SUMMARY](#executive-summary)
- [Foundation of KOK PLAY Development](#foundation-of-kok-play-development)
  - [Social Problems](#social-problems)
  - [Network Issues](#network-issues)
  - [Governance Issues](#governance-issues)
    - [Governance](#governance)
  - [Software Issues](#software-issues)
- [KOK Platform Structure](#kok-platform-structure)
  - [Protocol Blockchain (BaaP)](#protocol-blockchain-baap)
  - [BP Selection Algorithm (DPOSS)](#bp-selection-algorithm-dposs)
  - [BP Consensus Algorithm (PPBFT)](#bp-consensus-algorithm-ppbft)
  - [DApp Development and Implementation Environment (AutoXML)](#dapp-development-and-implementation-environment-autoxml)
  - [Distributed Artificial Intelligence](#distributed-artificial-intelligence)
  - [Open API](#open-api)
  - [KOK DApp Development Kit](#kok-dapp-development-kit)
- [KOK Ecosystem](#kok-ecosystem)
  - [KOK DApp Ecosystem](#kok-dapp-ecosystem)
    - [KOK Media Platform](#kok-media-platform)
      - [i. The Issues of Existing Media Platforms](#i-the-issues-of-existing-media-platforms)
      - [ii. Blockchain-based Media Platform](#ii-blockchain-based-media-platform)
      - [iii. KOK Media Products](#iii-kok-media-products)
    - [KOK Game Platform](#kok-game-platform)
    - [KOK Shopping Platform](#kok-shopping-platform)
      - [- Transactions between Individuals (P2P)](#transactions-between-individuals-p2p)
      - [- Transactions between Individual and Businesses (B2C)](#transactions-between-individual-and-businesses-b2c)
    - [KOK Mining Method](#kok-mining-method)
    - [KOK Wallet](#kok-wallet)
    - [Determining the Value of KOK Token](#determining-the-value-of-kok-token)
    - [KOK Value Determination Mechanism](#kok-value-determination-mechanism)
- [Evolution of KOK Platform](#evolution-of-kok-platform)
  - [Roadmap](#roadmap)
  - [Token Issuance](#token-issuance)
    - [KOK Coin Swap of KOK Token](#kok-coin-swap-of-kok-token)
- [KOK Platform Team](#kok-platform-team)
  - [Executive Team](#executive-team)
- [Vision of Blockchain Industry and KOK](#vision-of-blockchain-industry-and-kok)
- [Legal Notice (Disclaimer)](#legal-notice-disclaimer)


# EXECUTIVE SUMMARY
The global market for cultural content is expected to reach around 1,000 trillion won as of 2022. In particular, the portion of digital content is expected to reach 53 percent in 2021, compared to only 33.5 percent in 2012, and has grown rapidly by more than 20 percent annually.
In order to enjoy cultural content in the past, we had to go to a theater or a concert hall, but now we can easily enjoy all the contents with a mobile phone.

The digital content market displayed significant growth with the advent of digital content platforms such as Netflix, YouTube, and the Play Store, whiche nabled the active distribution of content anywhere in the world.

However, as globalization accelerates, the monopoly of several large platforms has deepened, resulting in greater platform influence over content providers.

Eventually, content providers are experiencing a vicious cycle of profitability, offering a huge fees to the platform while failing to seize the opportunity to properly expose their content. Moreover, as the platform has a huge influence in selecting content, the market has been distorted by the uniformity of the content according to the direction of the platform, and the content ecosystem is to be degenerated.

The recently emerged blockchain technology has demonstrated the potential of building a democratic system through its core value, decentralization. Certain blockchain technologies are not governed by groups or central forces, and all transactions and events are transparently disclosed. Therefore, there is no risk of forgery or counterfeiting. KOK Foundation has developed a digital content distribution platform through blockchain, noting the potentiality and possibility of blockchain technology.

KOK PLAY is a decentralized digital content platform that was created through the combination of our AI, big data, and the blockchain technology, which is currently in the spotlight. To solve the problem of monopolization of the existing global platforms, it was developed to realize three values: 'Fair, Share, and Enabler.' KOK PLAY is a platform that allows all creators to fairly exploit the assets of the platform(Fair), share values, vision, and fair returns accordingly(Share), and ensures creator’s freedom to create(Enabler). KOK PLAY will make the vision into a reality together with you.

* * *
  
# Foundation of KOK PLAY Development

## Social Problems

**Centralized System Service**

Existing platforms generate revenue by centralized service system. The Apple App Store and Google Play Store collectively take 30 percent of the profits generated from the downloaded apps. Not only it takes 30 percent of commission fees from paid downloads, but it also takes 30 percent of profits from in-app purchases. A centralized system service pays a high commission to an intermediary. Also, relying on centralized financial institutions to carry out transactions, which inevitably excludes large populations without bank accounts.

**Asymmetric Compensation Model**

The use of a centralized service model is tantamount to a repeat of a current asymmetric model. For instance, Facebook, Twitter and Instagram are setting up a multibillion-dollar company with unbalanced profits from stockholders and basic employees, community labor. Product revenues are granted to administrators, and actual content creators only get "performance," "badge" and "honor," thus reducing their collective drive to improve their products.

Bitcoin, the first blockchain, was designed to enable remittance to non-government-issued money between two anonymous parties via the Internet, within a specific group of people. Since 2009, the number of blockchain usage scenarios has exploded. Smart Contract, DApp, decentralized self-organization - activists around the world have worked hard to turn those concepts into a concrete framework for blockchain. It is natural that these attempts face problems. Ethereum co-founder Vitalik Buterin summarized them in his latest Post 2. Basically, we summarize it into some of the key words: governance, speed, waste, DApp usability and adoption. The problem is, "How do we create a blockchain that can address these four main issues in a decentralized and secure way?”

## Network Issues

**Efficiency**

Vitalik Buterin: "POW wastes billions of dollars a year, much more than the sum of all fraud and theft cases combined. It's a big tragedy."

Modern blockchain, even the most advanced blockchain projects, are suffering from the same problem. In other words, all transactions are being conducted one by one. This applies equally to proof of stake (POS) as well as to the proof of work (POW) blockchain. Transactions are stored one by one in blocks, and only one node is able to generate a block at one time. All of this brings the results of sequential execution of transactions and smart contracts. This turns the back of the blockchain network into a giant supercomputer, taking away 99.99 percent computing power.

## Governance Issues

**Centralized Infrastructure**

Vitalik Buterin recently said: “The Bitmain and Alliance Pool currently has 53 percent of all Bitcoin hash power. Isn't it a big problem?" Centralized network resources poses the risk of severe damage to the entire POW network, even with domination, penetration, or shutdown of a small number of targets.


### Governance
Vitalik Buterin: "Considering how EOS governance has been catastrophic, doesn't this mean that there is a fundamental flaw in all on-chain governance, including decentralized autonomy organization(DAO)? What decentralized self-organization is able to counter bribery attacks or plutocracy?" Governance has much to learn from existing methods, frameworks and attempts. In governance, there are a few things we need to fix from the beginning. Some should be changed later after evaluating the reality. Computer scientists are looking for the perfect solution for blockchain governance that is safe and protected from countless malicious decisions and exploits. Like the U.S. Constitution, a powerful system will be the foundation for future change that needs to take place later. We constructed much of the design with this only question in mind: "What is fair governance in cryptocurrency?"

## Software Issues

**Utility**

Vitalik Buterin: "Why there aren't any large applications that are useful yet?” Most blockchain applies several viable entities such as smart contract and chain codes. Use of newly invented or light programming language can reduce the reliability and expressiveness of the code. Smart contracts are short and simple. The languages and techniques used in blockchain do not allow the development of rich functions and powerful systems. Only a few smart contracts exceed 1,000 codes. However, complex business logic, rich content manipulation, and creating DApp that connects multiple users – made possible on the KOK Platform!

**Security**

Vitalik Buterin: "Why don't we have a good solution to solve our security challenges yet? When will the problem of account hacking and theft be resolved?" Most blockchain comes with only compilers that create executable code. There are no tools for device testing, continuous integration, and code analysis. As a result, only simplicity protects smart contracts from security breaches. Complex smart contracts have inherent flaws and vulnerabilities, and many reports on security incidents have already been submitted. If better development tools were provided to developers, security incidents that cost significant damage could be avoided. Thus, KOK Platform is considered as meaningful innovation by allowing complex function and creating efficient and productive environment for Dapp. We found answer to the most blockchain problems.

* * *

# KOK Platform Structure
The DApp, which will run on KOK Platform, can be seen as a service group that forms a single district or a sector. One DApp is similar to how one portal service is structured in the internet service.

“BP” is selected based on the “characteristics of symmetrical structure” drawn from Group Theory. Participating primary nodes are responsible for developing the DApp ecosystem and demonstrating KOK Platform safer and faster. In this symmetrical structure, DApp services find their similarities through “structuralization,” comparing the number of transactions, the node distribution, and the time complexity generated within each DApp service structure. This similarity works to group them in one large group, and it overcomes the limit of existing blockchain by optimizing similar structure within the group. We define it as GOS-BP (Group Of Symmetry-Blockchain Producer).

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/gos-bp.png)

A group of DApp services has a primary node that participates in the KOK Platform as a BP (Block Generation Node Block Producer Node), and is connected to this representative node to form its own DApp service ecosystem. This DApp service ecosystem resembles aspects to sidechains, but it does not have its own DApp coin, instead implements its function by linking and converging many Off-Chain services and DBs. Coins required for token explicitation including compensation, KOK, are allocated via KOK Foundation and used.

## Protocol Blockchain (BaaP)
The internet of values and trust is called the next generation Internet, and the essence of the Internet is called WWW(World Wide Web). If so, KOK expects that the essence of the next generation Internet will probably be the next phase of WWBW, which is the next phase of the WWW. Such blockchain is currently facing three dilemmas. Ethereum's founder, Vitalik Buterin, called these as the trilemma of blockchain. He also claimed that of the three characteristics of security, scalability and decentralization, all three cannot be achieved at the same time, and at most only two would be resolved. Many blockchains are trying to solve this trilemma. The same applies for KOK Platform.
Blockchain is often regarded as technological commodity that possesses public property characteristics, and viewed as newly formed Economic Layer on World Wide Web. Trust and fundamental value essential to the economical contract and transaction are guaranteed by the Economic Layer, the blockchain protocol. Numbers of DApp appear to be created more easily by considering block chain as Economic Layer, and the World Wide Web is moving towards the next level of the Web: the WWBW - World Wide Blockchain Web. KOK Platform is one of this BaaP, which will allow many DApp to be easily created on top of this platform.
The technology enabled this process is called AutoXML, which fully implements the data standard defined by the World Wide Web Consortium as an automated engine. AutoXML technology empowers blockchain to become another protocol layer, and allows two-way data transport that immediately shown on the Web via data standard.

## BP Selection Algorithm (DPOSS)
The node that is delegated to generate the block and determine the main policy is called the Block Generation Node - Block Producer (hereinafter BP), and all of DApp are eligible to become BP. The selected DApp provider is compensated for its role as a block generator. The methods and conditions of becoming BP are as follows:

**1. BP Selection Method**

- BP is selected among DApp providers that provides the high quality DApp services.
- The selection method is ranked according to the votes of coin holders and the service utilization rate.
- Selected BPs are compensated for block generation.

**2. Conditions to be BP**

- In order for a DApp to become a BP, a node server must be established and operated.
- Server deployments cost approximately $500 per month for using cloud services with minimum specification.
- Even with investment costs, higher returns can be achieved with given block-generating rewards.


## BP Consensus Algorithm (PPBFT)
Initially, the BP that forms the KOK MainNet begins with 21 number of BPs, and each BP forms the single Region by three BPs.

- One BP has two logic layers. The upper layer is the Service Layer and the lower layer is the Communication Layer that is responsible for consensus. In case the DApp is dysfunctional or not ready to operate when the MainNet is launched, the BP representing DApps enters into the MainNet as Dummy BP while running only Communication Layer (lower layer).
- The seven Regions are fixed before the start of the MainNet, taking into account the distribution of global telecommunication networks and the DApp.
- Each Region has its own index for its initial MainNet creation, called the Block Region Index (BRI), with numbers from 0 to 6.
- Each BP has its own index, which is called the Block Producer Index (BPI). The BPI is fixed at initial MainNet creation and the given number is from 0 to 20.
- The index for each BP extends to the adjacent Region and increases. In other words, Region 0 has BPs with BPI 0, 7, 14 and Region 1 has BPs with BPIs 1, 8,15, thus Region 6 has BPs with BPIs 6, 13, and 20.
- A certain time zone where blocks are generated is called the Block Generation Period. During the period, one BP is responsible for the initial block generation and that node is called the Primary BP. Twenty-four blocks are created during the one block generation interval. (The number of blocks to be created in one interval can be adjusted through further simulation and testing)

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/ppbft.png)

- Primary BP is determined during the previous block generation period. The method is decided by the outcome of function MOD21 which is a module for the last four byte value of the 21st block’s hash generated during the previous block production interval. The result of MOD21 function is integer between 0 and 20 regardless of its input value. This value is the exponential value of the BP that will be the next Primary BP. (The block selected to determine the next Primary BP is currently fixed to the 21st block. However, the selection algorithm will be changed in a later version.)
- Six BPIs are obtained by adding 1,2,3,4,5,6 to the index value of the Primary BP then applying the MOD21 function. These six BPIs are ‘Lead BP’ of each Region among neighboring BPs. In the block generation period, Lead BP serves as a leader to draw consensus in its Region along with Primary BP and notifies the result to the Primary BP.
- Primary BP propagates its initial block to the Lead BPs of neighboring Regions, and the Lead BP of each Region propagates the received block to the other two BPs of its own Region to verify the consensus. The consensus algorithm used is PBFT (Practical Byzantine Fault-Tolerance).
- Each Lead BP sends the consensus result of its Region to the Primary BP. The consensus algorithm used this period is also PBFT.
- The consensus algorithm applied comprehensively to KOK Platform is PPBFT (Parallel PBFT).

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/mod21.png)


## DApp Development and Implementation Environment (AutoXML)

**Standardization of W3C and Data**

W3C (Worldwide Web Consortium) standardized for the data exchange over the Web and data representation for data transfers in 1998. The meta language used for this standardization is XML (eXtensible Markup Language). However, XML has very difficult attributes for grammar and tags for editors and people to program. The XML solution that automates and makes it easy to write is AutoXML.

**HTML vs XML**

Web is very important for the blockchain application service, DApp. Because it is possible to show people through the Web and interact with information. There are two ways to express data in the Web: HTML and XML. HTML is unilateral and intended to show people, but XML is bilateral that allow data to be sent and received in addition to what it shows. This property allows to program the Smart Contract for creating DApp

**Smart Contract Composition**

Even the basic languages such as Solidity are not programmed, but is maneuvered in drag-and-drop format to compose smart contract.


## Distributed Artificial Intelligence 
- Artificial intelligence is widely applied in KOK Platform.
- First, each DApp provides media curation by utilizing AI suitable for its own ecosystem.
- Second, each BP uses distributed AI functions to cooperate with the neighboring BPs for robustness of KOK Platform and load balancing.
- Thirdly, the KOK Wallet is equipped with AI function to perform as a function of personal data safe and generates economic benefits through proper data analysis.

## Open API
The DApp, which will run on KOK Platform, can be considered as a service group that forms a single sector. It is similar to one portal service was formed at Internet service in the past. A group of DApp services sector has a primary node that participates as a BP(Block Generation Node) in KOK Platform, and establishes an ecosystem of DApp services around this representative node.


## KOK DApp Development Kit
KOK DApp Development Kit (KDDK) will be prepared for the development of DApp that operates on KOK Platform. KDDK provides all the tools and environments needed to develop, test and operate the DApp to be launched on KOK Platform.

* * *

# KOK Ecosystem
The KOK ecosystem is designed to be connected and evolved organically by three main elements.

**KOK MainNet**

BPs created based on GOS-BP concept connect to form a network of consensus. KOK Coin is the key cryptocurrency of the KOK MainNet and the KOK ecosystem.

**KOK DApp**

Each DApp has one BP that represents it, and that BP manages the sub-ecosystem of that DApp, or DApp ecosystem. DApp is an integrated content ecosystem that provides a variety of digital content. The DApp ecosystem mostly uses KOK Coin provided by the KOK MainNet, but in special cases, it can design its own DApp coin, in which case the exchange mechanism with the KOK Coin will be described later.

**KOK Play Wallet**

KOK PLAY Wallet is a device for fair value sharing between BPs of mainnet, and participants of the mainnet and DApp. The KOK PLAY Wallet is also connected to the DApp, making it easy to purchase content through the wallet.

## KOK DApp Ecosystem
KOK Platform is an integrated content platform that provides a variety of contents. Content is easily available within KOK Wallet. The KOK ecosystem consists largely of three themes: "KOK Media Platform," "KOK Game Platform" and "KOK Shopping Platform."

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/kok_dapp_ecosystem.png)

Each platform solves the problems of existing services and utilizes blockchain technology to pursue the standard of the future platform in a more transparent and advanced form.
KOK Platform, which is creating the World Wide Blockchain Web (WWBW) through the blockchain, an Economic Layer , has designed the Token Economy that creates and profits from many DApp.

### KOK Media Platform
KOK Platform resolves problems arising from existing media such as YouTube, Facebook, Netflix and Tungshin Spin(Tencent Video), which combine blockchain to create a transparent form of blockchain-based media video platform.

#### i. The Issues of Existing Media Platforms 
Existing media platforms have problems such as ‘measurement of advertising fees', ‘distribution of revenue' and ' protection of personal information.'.
On YouTube, on average, more than 1 billion hours are watched by platform users a day, but there is a conflict of interest between advertisers and platform executives. Issues that are difficult to solve in centralized systems, such as opaque revenue sharing between Contents Creators and platform companies, and the theft and hacking of personal information data, such as Facebook information leaks, have recently emerged.

in addition, issues such as compulsory viewing of advertisements by platform users and view abusing to generate revenue for creators are being raised, and additional issues must be solved to reduce economic losses incurred in the media platform.

#### ii. Blockchain-based Media Platform

**(1) Problem Solving between Advertisers and Platforms**

Unlike the fact that advertisers want to effectively place ads on certain channels where ads can be exposed to desired target audience, advertisers complain about "targeting" and "efficiency of advertising" and pay less due to the existing platform's placement of ads on the viewbot and on the unhealthy contents. As a result, content creators complain about reduced revenue and centralized platform.

**Remove the 'Viewbot' Abusing**

The process of distinguishing 'viewbots' from general users can seem quite complex. In the KOK ecosystem, users can freely consume based on KOK Token. Therefore, the criteria for screening real users of KOK Token are determined by setting specific conditions for consumption of KOK Token, and distinguishing them from the 'viewbots' to simplify the problem of distinguishing them from actual users.
The platform distinguishes "viewbots" from actual users by creating devices such as "staking" of KOK Token within a self-verified KOK Wallet, "token consumption" at a certain level and "user activity" in wallet. In addition to the media, as our platform is operated based on based the consumption environment of user online such as use of KOK Token in games, music services, e-commerce, etc., it is not difficult to distinguish between real users and "viewbots.”

**Improve the Efficiency of Advertisement & Targeted Advertisement**

In blockchain, it is not possible to manipulate ratings and reputations. Transparency in the absence of an “abusing bot” becomes a powerful advantages. Advertisers will be able to distinguish high-quality channels and videos through ratings within KOK content platform, and to advertise efficiently based on data provided by viewers. Advertisers purchase KOK Token in the market, and the purchased KOK Token is consumed again by platforms, users and creators, so the ecosystem of KOK Token is completed in the form of a virtuous cycle.

**Competitiveness between Channels and Videos**

To limit the competitiveness of inappropriate channels, the channel will be evaluated using KOK Token. Using cryptocurrency to grade the system is very helpful in terms of vitalizing the ecosystem. However, when looking at the case of introducing a rating system using cryptocurrency, similar to this among DApps already in service, users are looking to increase their ratings on each other in order to get a big reward, resulting in problems that are much different from their previous intent.

To be recognized as a regular user, “abusing bot” must 'spend' KOK Token within KOK Wallet, and ‘be active' within the Wallet ecosystem for a specific period of time. These requirements effectively reduce the economic added value of the abusing bots and limit the approach.

KOK Platform effectively blocks the abusing users, and uses KOK Token to establish the subscriber and video rating system of the channel.

Users who consume KOK Token and watch are able evaluate the videos, and users who consistently make the appropriate evaluations receive more rewards than KOK Token they spent in their evaluations and subscriptions for providing "viewer data" to the platform.

The channel "Subscription" is proceeded through KOK Token staking and limits the total amount of staking, making the channel with a large number of subscribers highly influential. By providing rewards to channel creators according to the total number of staking on the channel, effectively producing quality channels and screening.

**(2) Issues between Creators and Platforms**

The process of ‘profit payment’ that content creators receive, which is currently the most problematic issue for video platforms, is one of the best issues to address when utilizing blockchain. In existing platforms, considerable conflict with the platform occurs due to issues such as the 'payment period' or 'transparent payment' for advertising fees, and the 'modification of algorithm policies' in which the creator is paid.

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/pop.png)

The Proof of Participation (POP) solves the problem in the form of a participation proof method in the following ways:

1. Watch time for a certain N hours.
2. Click on in-video ads
3. Number of video ratings

The KOK media platform's algorithm calculates all interactions in content, stores each user's video viewing data in a blockchain, and pays the content provider transparently. Payments of these costs are generally paid in proportion to viewing time, supported by an auxiliary content evaluation algorithm, measured and paid precisely.

**(3) Issues between Users and Platforms**

Media such as YouTube and NETFLIX have begun to emerge, and personal data has also become important assets. Recently, the biggest problem with Facebook and YouTube has become a social issue as privatization of individuals' data, which is not in the form of rewards for users.
In particular, Facebook's recent leak of personal information has been a shocking incident around the world, and the encryption of such identity data is considered an essential. On KOK Platform, identity data is encrypted and stored in blockchain, and data required by advertisers such as type of individual viewing and viewing age are collected with consent and compensated with KOK Token.


#### iii. KOK Media Products

KOK Platform provides its own media products in addition to media platforms that allow platform users to upload and share videos. The media products autonomously are shared with people around the world by uploading music, dramas, entertainment, movies, and performances that have already been released to the market with a business value.

With K-pop (Korean Popular Music), which is gaining huge popularity around the world, the company aims to provide music services in conjunction with the KOK PLAY platform and Korea's flagship music platform, which can introduce, stream and download pop music.

In addition to K-pop, representative dramas of Hallyu is also provided by KOK PLAY platforms, and services representative entertainment of various channels, including original KOK PLAY Entertainment. KOK PLAY platform also serves films of various genres.

By holding performances of representative artists for K-pop and performance of overseas artists, the live broadcasting of performance service is provided by KOK PLAY platform, along with ticket sales for performances.

**Influencer System**

KOK Platform supports the activities of influencers within the 'KOK Media Platform.' Influencers with great influence and potential in the cultural industry and e-commerce market appear on various media content on KOK Platform and attract users' attention. Influencers provides content to users, and users can express their interest in the influencers with KOK Tokens. Advertisers can also request advertisements from the influencers through KOK Platform, and advertising fees are executed through KOK Token. Advertising contracts within these platforms contribute to the increasing value of KOK Token in the market and the active transaction of KOK Token.

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/influencder_system.png)

Transactions between nodes form a block with tokenized reward tokens, and are traded within the platform. KOK Platform transparently discloses transactions to enable trends analysis of reward tokens among advertisers, influencers, and customers and analysis of data through token.

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/kok_platform.png)


### KOK Game Platform
**Problems of the Existing Game Industry**

In addition to the development costs, game developers suffer from marketing costs, fees caused by Store Platform such as Google Play and the iPhone App Store. The amount of Investment made for research and maintaining proper entertainment is already significant to the small and medium size game companies. Therefore, it is difficult for these companies to cover extra expenses occurred through the platforms. These out-of-game expenditures cause the decrease in the game quality due to reduction in budget for game development.

Equitable operation of game makes users to be more faithful towards the game. Till these days, gamers have obtained suspicions on the probabilities of random selection while purchasing items such as “digital asset lottery” to acquire items in the game. Gamers invest considerable amount of time and money to draw good items, but the process has never been transparently exposed. Consequently, gamers always hold some questions on its irrationality.

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/game_platform.png)

Moreover, ownership of the game items is often unilaterally extinguished due to the service disruptions or the conditions, and service terms given by game suppliers. The issue of deficient item ownership for gamers who dedicated significant amount of their times, is a challenge that needs to be addressed in the global game market. As such, existing games have a problem of cost and reliability within the game. The KOK game platform within KOK Platform solves the problem through blockchain technology.

The KOK game platform is a global game platform that makes payment easier and more convenient by utilizing KOK Token. Instead of paying nearly 30 percent as service charge to platforms such as Google Play and iPhone App store, much cheaper commission policies of the platform help game developers to reduce their burdens. 2. Additionally, the platform implements targeted ads for appropriate users by comprehending platform users’ demand with artificial intelligence(AI).

KOK platform also provides open data to outside developers, so they can create quality games. In addition, API manuals and direct engineering support are given for the blockchain-based game development. The probability of ‘digital asset lottery’ in the game is set by random number generation that is resulted from the participation of KOK Platform, game players, and game operators. Digital asset transactions take place based on Smart Contract and are transparently disclosed in blockchain.

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/game_process.png)

**Public API**

KOK Platform hosts smart contracts through public APIs. XML-RPC protocol is utilized to materialize smart contracts with token within KOK Wallet. In case of an item exchange in game, the item is registered as a registry smart contract and the item is publicly disclosed to all users. Based on the web and mobile for smart contracts, APIs have been developed for process management.

**Game Platform in KOK Wallet**

KOK Blockchain-based games generally serve within 'KOK Wallet'. The transaction requested between the KOK platform user wallet and the KOK-based games is generated through APIs. When the transaction takes place, KOK Token is moved between wallets. At the time when transaction occurs, related information is presented to users. Users can easily accept or reject the transaction, and it allows blockchain transaction to be more convenient.

### KOK Shopping Platform

As Ethereum’s founder, Vitalik Buterin, noted, blockchain technology is more suitable for proof of inexistence rather than assurance of the value. For instance, if you trade luxury goods and attempt to use blockchain for proving its transaction, occurrence of the transaction can be proven. However, you cannot prove the actual value of the transaction. In other words, you cannot prove that the traded good is a luxury or not.

If blockchain has the difficulty of proving its existence, we need a trusted institution to confirm its existence and an equipment to perform corresponding activity.

Blockchain refers to a P2P type of personal-to-person transaction system with no specific manager or owner. Similar to traditional download methods in P2P format, blockchain technology proves the transaction content by storing it on globally distributed computers.

As mentioned earlier, such blockchain is able to prove the non-existence but not suitable for confirming its existence. Therefore, the blockchain requires a transaction with ‘trusted institution’ or ‘trusted person.’ Rather than being stored in decentralized ledgers, these trusted institutions or persons require guarantees of government and agency, or separate supervisory.

KOK Platform guarantees property and goods traded among KOK Foundation and external regulatory institutions(or certificatory agencies). The platform also supports transactions between individual and business(B2C) and among individuals(P2P) on specific goods or services.

#### - Transactions between Individuals (P2P)
Fraudulent activity by buyer and seller is the first issue that need to be prevented in terms of transaction of goods or products between individuals. The purchaser will place the “KOK Token” or other cryptocurrency in escrow account(e.g., “USDT”) before the transaction, and the cryptocurrency in the account can be withdrawn with the consent of two out of the three parties. Transaction commonly take place with the consent of the purchaser and two sellers, but withdrawal can also be made after elapsing a certain period of time in case of no-objection from the purchaser.

However, in the event of a dispute between the seller and the buyer, a third party shall intervene to handle the dispute. Seller and Buyer select ‘conflict mediator’ based on the mutual agreement reached after analyzing reputation and ratings within the community. Then they request one to participate the transaction as an arbitrator. These systems are intended to establish a decentralization network that does not involve any intermediate interventions.

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/p2p.png)

**The Conflict Mediator**

Anyone within KOK Platform can be a "Conflict Mediator." “Conflict Mediator” plays an active part within the community and gets a chance to be selected. Rating of the mediator can be increased based on the commission received after resolving the dispute. Furthermore, buyer or seller who lost in the conflict can request KOK Platform to reconcile the dispute, so the transaction can be paused. If KOK Platform raises objection to the dispute, one can demand additional ruling by paying extra charge. KOK Platform elects “Jury” through random selection within the community and allows them to resolve cases internally. If there is a legal problem subject to certain country, the transaction is suspended in accordance with the law of the country concerned. If the legal issue is raised based on the ‘international law,’ corresponding transaction is discontinued in accordance with international law.

**Jury**

To create equivalent jury selection process, a random hash value, generated by the KOK internal transmission, is converted to select juries from 100 ‘conflict mediators’ who are ranked high in the community. To Prevent manipulation, the whole process of converting hash value is disclosed for the complete transparency and the result random value can be verified. This effort of creating the fair process and results forms trust among stakeholders. Adjustments are resolved according to the majority's opinion, and if the majority does not agree, the jury's screening and dispute settlement process shall be repeated until majority consent is obtained.

**Dispute Mediator and Jury Compensation**

Dispute mediator and jury are compensated with a certain percentage of sales when the dispute is resolved. Compensation will be rewarded with KOK Token and will increase the rating within the “KOK Shopping” platform community. The rating can increase the probability of being selected as a “Conflict Mediator” in the future cases. As a result, the cumulative revenue occurred by the dispute resolution can be significantly raised.

#### - Transactions between Individual and Businesses (B2C)
For transactions between individuals and businesses (B2C), goods and services from a number of proven partners (branding) are provided within KOK Wallet. Goods and services within the KOK Wallet will be a window of opportunity to promote to people around the world within KOK Platform ecosystem, while Korean wave content and products offered by KOK will bring huge marketing effects to KOK Platform.

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/b2c.png)

In order to expand the ecosystem of KOK Platform and improve services, the representative nodes within the KOK will select a majority of brands that can provide goods and services to the KOK shopping platform. Validated brands promise quality assurance for goods sold and record transactions (TXs) that are made based on the hash value, leaving them in the other party's wallet to prove the transaction. A purchaser with proof of a transaction may request a warranty for quality based on the transaction, and does not guarantee quality in the case of a third party without a transaction.

**Store & Utilize Consumers’ Big Data**

Personal information set by consumers according to data delivery, search data by consumers, data related to consumer consumption patterns are integrated and uploaded to user big data servers on KOK Platform. Consumption data of users uploaded to big data servers are accumulated and based on the formation of user big data in the ecosystem, serving as valuable information in analyzing and understanding patterns of online shopping activities.

Consumers within KOK Platform will receive certain rewards as providing information to consumers in KOK Platform ecosystem is an act that contributes to the formation of the value of KOK Platform. Consumers can receive customized data based on data provided on the contrary, rather than unilaterally providing data to shopping malls and certain brands.

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/app_data_blockchain.png)

**Consumer (user) Rewards**

In online shopping, consumer data is utilized in a variety of ways. Consumers can be compensated for KOK Tokens while providing the data to the KOK shopping mall or brand. In addition, when you receive custom ads, you can receive a KOK Token as a reward.

Brands within the KOK shopping mall can receive data on target customers by purchasing KOK Tokens in the market and paying them to KOK Platform and consumers. Based on this information, KOK Token is paid to the platform to effectively proceed with targeted advertising.

While collecting data, the KOK shopping mall rewards KOK Token and provides the data to the brand inside the KOK shopping mall. In addition, it will be paid with a KOK Token while running targeted ads, contributing to the value of KOK Token.


### KOK Mining Method

The "Delegated Proof of Stake & Service(DPOSS)“ pursued by KOK MainNet solves the problems of the existing POS method and DPOS. The simple POS method has a low return on individuals and the POS-based master node method of mining has the disadvantage of requiring individuals to have a considerable number of tokens to form nodes. Also, simple DPOS now has a governance problem called ‘collusion'. It has been criticized as a governance issue, where most of the profits could go to a handful of interest groups that collude and create nodes.
On ‘DPOSS’, BP is selected from DApps that provides quality services. BP selection depends on the existing voting method and the degree of service activation in the DApp, using the following measurement methods: 

1. Vote
2. DApp Usage Rate
3. DApp Sales

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/mining.png)

### KOK Wallet
![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/kok_wallet.png)

In addition to the basic contents of games, media and shopping, KOK Wallet offers several additional functions for the development and stabilization of the KOK ecosystem.

1. Staking and Voting
2. KOK Lease(P2P)
3. KOK Invest(P2P)

KOK Wallet provides the KOK staking function. A structure in which tokens is staked to the BP of their choice, and in addition to the block generation revenue occurred when staking KOK Tokens, receive a portion of the revenue from the revenue generated by DApps, which provided by the BP.

In addition, KOK Wallet allows to P2P lease between users of KOK Token for creating a positive value of KOK Token. By providing 'KOK lease' and 'KOK invest’ functions, investors will be able to hold and consume KOK Token stably.

The lease of KOK Token can be traded by selling it at a high price at a time when the KOK price rises and returning the amount equivalent to the stable asset "USDT" at the time of the lease. On the other hand, if the KOK price falls, it will be sold at a lower price and should be returned to the lender as much as the assets at the time of the lease.

On the other hand, if 'KOK Invest’ function is used, profit equivalent to the amount of the investment can be obtained. In this case, if KOK Token falls, the return of USDT at the time of initial investment results in an additional reduction in profit. Conversely, if KOK Token rises, it does not earn returns on the price increased portion of KOK Token.

When the price of KOK Token rises, it is possible to make a profit by selling it at a high price using the 'KOK lease'. Conversely, if the price of KOK Token rises when the 'KOK invest' is used, it generates as much profit as profit revenue, but no return on price increases difference. However, it is possible to make a stable investment since it receives profits from the principal.

The distribution volume of the initial KOK Token is a structure that is slowly distributed as profit received through staking or using the 'KOK Investment Function'. Initially, there is a restriction on the use of 'KOK Lease' because the use of 'KOK Lease' requires the payment of expense in KOK Token.

**• Security**

The KYC, which is based on biometric authentication such as face or fingerprint, provides a KOK Wallet service that allows users to log in to their accounts and use them conveniently without managing their personal keys.

**• P2P Transactions**

P2P direct transactions are not supported between early KOK Wallets. It will be possible from the release of the KOK MainNet and the KOK-only wallet, and from the Milestone 4 (September 2020) when KOK Token is swapped for KOK Coin.

**• Interlinkage of KOK Wallet and DApp**

The KOK Wallet can also be used as an in-app form within the KOK DApp, and or as a terminal node for the KOK DApp. It supports development of DApp by implementing KYC at the level of real-name authentication through mobile phone authentication and supporting AML

### Determining the Value of KOK Token
KOK Token is determined in various ways within the ecosystem and is based on several key elements.

**(1) Platform Sales**

Revenue from advertising, streaming services, etc. will be received from advertisers or consumers of platform services through KOK Token, which will be generated from each content (games, music, video, etc.) within the platform provided directly by KOK Platform. Advertisers or consumers must purchase KOK Token in the market, which affects the value increase. Part of the platform's revenue is again compensated for token holders.

**(2) DApp Sales**

Advertisers and consumer service DApp are purchasing tokens in the market for spending. This is again returned to the token holder as some compensation, but still affects the value to increase.

**(3) Platform Supply Revenue**

In return for providing the DApp services to existing users, KOK Platform will return part of its sales within the DApp to KOK Platform. A portion of generated revenue will be used to compensate to the token holders.

**(4) Increase in KOK Investors**

Based on the decentralization, general cryptocurrency is used as a method of storage. Most of the coins have built some sort of a minimum of basic value within the market. In addition, if many investors are interested in KOK Token and invests in it, it acts as a relatively stable value storage tool, and it may result in value increase.


### KOK Value Determination Mechanism

The value determinant of KOK Token is distinguished into numerically measurable and non-measurable parts.

Profits from 'profit on platform sales' and 'profit on platform provision' from providing platforms to DApp are quantifiable. Adjust the amount compensated to token holders by less than 50 percent of the total sales (sales+supply revenue),and contribute to the market value of KOK Token to rise for the remaining 50 percent or more of the proceeds . Therefore, it has a positive effect on the value of KOK Token.

In addition, areas that are difficult to calculate numerically, such as 'KOK Token investors increase' or 'platform service fees' that determine the value of KOK Token, are also designed to contribute to the increase in the value of KOK Token by influencing the market price.

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/kok_value.png)

When using "Staking" and "KOK Invest" on KOK Platform, ‘reward earnings’ and ‘lease revenue’ will occur. Respectively, using "Staking" and "KOK Invest," tokens exist within the wallet will not be distributed outside, which acts as a device that significantly reduces the sale of KOK Tokens.

If the number of users using KOK Platform continues to increase, sales will also increase proportionally. The typical investor is a 'Risk Averter' and therefore strives to achieve stable ‘reward earnings’ and ‘lease revenue’ within Wallet. If the market does not see a rise in token prices above “platform mining revenue“(‘reward earnings’ + ‘lease revenue’), the sale of KOK Token in the market is limited.

If the market price increase rate of KOK Tokens is higher than the ‘platform mining revenue', investors will evaluate KOK Tokens based on the price formed in the market, trading of KOK Tokens will be activated in the market. On the other hand, if the market price increase rate is lower than ‘platform mining revenue', it is relatively advantageous to purchase KOK Token within the market and move it to the Wallet to use the stake and invest function. In this case, the circulation of KOK Tokens in the market decreases, which is the factor in reducing the selling in the market. Through this mechanism, which ‘platform mining revenue’ contributes to the rise of market value of the token, the foundation will complete the stable market value for KOK Token.

* * *

# Evolution of KOK Platform
## Roadmap
The KOK ecosystem has the form of improving existing digital content business models to the form of DApp and transferring them over blockchain.
 
![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/kok_roadmap.png)

## Token Issuance
Total issuance of KOK Tokens for lifetime is 5 billion, mining 1.5 billion (30 percent of the total) in the initial five years according to the issuance schedule.

Token allocations prior to the launch of the mainnet are allocated to users of KOK Platform under the agreement of KOK Platform and the DApp mounted on KOK Platform. KOK Token is distributed either by compensation for the provision of data information by users using the initial KOK Platform, or by placing the stake on the initial KOK Platform and the DApp service.

After the launch of Mainnet, BPs will be compensated for block creation, while token holders cast their ballots and staking for BPs will be rewarded according to BP's policies.

The total number of issues set at 5 billion is to maintain steady compensation for BPs after Mainnet. The actual volume of distribution has been gradually burned since 1.5 billion issued in the first five years, reducing the total amount of distribution.

As can be confirmed earlier, part of the sales of KOK Platform goes back to the platform users as a staking reward, other part will be used or burned to raise the value of KOK Token. KOK Platform continuously burns some of KOK Token generated by sales, contributing to the value of KOK Token. On the other hand, a stable amount of KOK Token should be provided to BP each year as a block compensation.

KOK Platform and BP set compensation for the generation of the block under consensus. Block compensation for that year shall not exceed the amount of burned tokens in the last year. Additionally, KOK Platform and BP also identify the degree of user staking, and the higher the average number of staking in the past year, the closer the amount of block compensation for that year can be to the amount of burned tokens in the previous year.

DApps and nodes that contributed to the development of early KOK ecosystem and to the construction of the platform comprising ‘KOK Platform,’ ‘media platform,’ and ‘game platform’ will be rewarded KOK Token according to the initial plan.

Allocated tokens are reallocated in proportion to the users using the corresponding DApp and to the staking token. According to the DApp's policy, the token will be distributed over different periods within different reward structures.

![image](https://raw.githubusercontent.com/KOK-Foundation/Documentation/ca84fbbe1866947a5cfd6952c471bc8e52f3da71/en/images/token.png)

### KOK Coin Swap of KOK Token
KOK Token, initially issued in ERC20 form and issued up to the point when the MainNet of KOK Platform is prepared and the key coin of KOK ecosystem is prepared (Milestone 5) , will be swapped 1:1 to KOK Coin.

* * *

# KOK Platform Team
KOK Foundation is the main body that develops and operates KOK PLAY. (https://kok-play.io/ )

## Executive Team

**CEO Dong-seop Hwang**

CEO Dong-seop Hwang is currently the general CEO of The Groove Company, founder of The Groove Entertainment, co-chairman of Gom Pictures, and director of the Korea Entertainment Producers Association. As a Korean entertainment producer, he produces various contents ranging from albums, dramas, movies and entertainment. He produces albums such as singers Freestyle, MC Han-sae, Big Mama Soul, Wanted Kim Jae-seok, Park Hye-gyeong, Han-byul, and dramas OST MBC's 'Best Love', MBC' Road No. 1," KBS's 'Wangs' Family' JTBC "Padam Padam"and SBS' "Remember," KBS "Good doctor," etc OST's were produced. and have taken part in producing MBN drama "Love Alert," coproduction, movie "Dukgu," “Real Criminal," "The 8th night."

Among the award-winning prizes are the 2016 Korea Creative Content Agency Award for Achievement in the Pop Culture, Arts and Culture Industry Development Division, 2014 Korea Creative Content Awards, 2014 Award for Overseas Proprietary Contribution, 2014 Award for Culture Exchange and Sports Tourism, 2014 Korea Entertainment Producers Association for Achievement in Popular Culture Industry, and 2014 Award for Drama Producers for the 21st Korea Culture and Arts Awards for Arts. For his final education he have received a master's degree in advertising and public relations at Yonsei University's Graduate School of Journalism and Public Information.

**CTO Young Choe**

CTO Young Choe is an evaluation expert of ICObench, founder and CEO of Crypto Valley Lab, Inc., and a professor at Yonsei University's College of Technology.
He has been an advisor to a number of global blockchain tasks, including Q DAO, EdenChain, GBC Korea (UCX), EOS Chrome, EDC Blockchain, ACCBY Chain, ID&D (ED coin), and Bolt Protocol. He also serves as an editor of Blockchain Today, a monthly magazine on current affairs in the blockchain sector.

He has served as general representative of Co-Founder / CTO / Technology of the 4th generation cryptocurrency and the DApp platform, the Color Platform. He majored in software engineering and system software at North Carolina State University in the U.S., worked at BMC Software San Jose Lab, Software Corporate Lab at Samsung Electronics, NVIDA R&D Center in Korea, SK Hynix Leading Laboratory in U.S., 3K Software USA, Software College at Sungkyunkwan University, and has demonstrated his ability in theory, practice and technical management. In particular, he has been an expert in concept design, architecture design, revised and reverse ICO, and on-and-off chain integration in blockchain area.

He is also active in spreading ecosystem of open-source software such as Linux. He served as the founding director of the Korea Blockchain Industry Promotion Association (KBIPA). CTO Young Choe also serves as the CSO for 3KFinance, a company specializing in Crypto-Finance and Cybersecurity. In 1980, he graduated from Seoul National University with a degree in atomic nuclear engineering. (https://www.linkedin.com/in/young-choe-8033684/ )
 
**COO Ji-won Kang**

As a mobile game developer, He is developing various genres of games and has signed a publishing contract with Smilegate and Chu Kong, China, by developing Mobile version of "Battle of the Three Kingdoms" based on Naver's webtoon "Battle of the The Three Kingdoms." Currently, the company has developed the mobile action RPG "Magia: Charma Saga," which received a total investment of $7 million from Nexon Korea, and is currently serving 130 countries around the world.

As a member of the external writing committee of the Korea Creative Content Agency, he participated in the production of white papers on content from 2013 to 2014. He served as a professor at the Graduate School of Hanlim University and has a master's degree in entertainment content at the Graduate School of Inter110national Tourism at Hanyang University.
(https://www.linkedin.com/in/g1-kang-6b134567/)

**CSO Sung-jun Park**

CSO Sung-jun Park is in charge of platform design and strategy at the KOK Foundation. He participated in Dungeon & Fighter and Cypher's services, the world's No. 1 game, at Nexon, and was responsible for paying model and game service of Azar service with 200 million users worldwide at HyperConnect.

In particular, as the CEO and founder of game development studio Netker Inc., he developed online game Versus and mobile game Mobius, and attracted more than $3 million investment from companies such as Smilegate. He has graduated from Seoul National University in 2010 with a degree in business administration.

* * *

# Vision of Blockchain Industry and KOK

**'Industry 4.0 & Creating New Momentum Seoul 2019'**

KOK Foundation held "Industry 4.0 & Creating New Moment Seoul 2019" at the Dragon City Hotel in Yongsan-gu, Seoul on Sept. 30 and presented KOK Platform strategy and vision, introducing examples of promising sectors that were recreated by merging with existing industries during the Fourth Industrial Revolution.

At the first part of the conference, lawmakers from the ruling and opposition parties and representatives of major industries shared their thoughts and directions on future industries, while the second part of the conference focused on KOK Platform, which was built on the technological prowess of innovation in the Fourth Industrial Revolution.

* * *

# Legal Notice (Disclaimer)
KOK Coin does not have the legal nature of securities or stocks. Therefore, KOK Coin does not grant any rights to dividends and profits. When the sale of KOK Coin is completed, no refund is possible. Since KOK Coin does not have the nature of shares, holding KOK Coin does not guarantee the right to attend KOK Foundation meeting. KOK Coin does not guarantee any specific rights or values outside the blockchain platform. Therefore, it is not possible to use KOK Coin for speculation or investment purposes. This white paper is not legally binding and does not constitute any contractual relationship.

Efforts are made to provide accurate information on the contents of this white paper, but the information posted is subject to change and no responsibility shall be taken for its accuracy and completeness. The investor shall make its own project investment decisions by conducting a thorough investigation into relevant information and regulations and shall be aware of the relevant laws of the jurisdiction.

KOK Coin acquisition and storage may include a variety of risks. The risks include KOK Foundation launching blockchain, failing to improve its technology or failing to provide the services mentioned above. Therefore, before acquiring KOK Coin, all users and investors should carefully consider the risks, prices, and benefits of acquiring KOK Coin. If necessary, the foundation asks investors to seek input from experts in this regard. It is recommended that buyers who do not understand or cannot accept these risks and the separate risks specified in the terms and conditions shall not purchase KOK Coin.

The white paper prepared by KOK Foundation (or the Company) is only intended to convey information regarding the proposed coin launch to potential buyers of KOK Coin (or token). The information in the white paper may not be complete and does not imply any element of the contractual relationship.

The whole purpose of this white paper is to provide reasonable information to potential holders. Nothing in this white paper is in the form of proposals or investment concessions, nor does it include any form of solicitation or offer to buy securities within particular jurisdictions. In addition, nothing in this white paper constitutes an advertising or marketing publication and has nothing to do with the offering or purchase of securities within its jurisdiction.

This white paper is intended only to describe the KOK project (technology solutions), does not include any comments or commitments, and do not guarantee that our final goal will meet your expectations in terms of feasibility, feasibility and competitiveness of this project. KOK Coin purchasers must agree that they have a good understanding of this white paper and legal notices, and that they are committed to complying with the laws of their place of residence, especially the laws of money laundering and prevention of terrorism, and have sufficient experience and understanding of cryptocurrency and blockchain technologies. This white paper will be distributed in Korean and other languages. In the event of an interpretation dispute, the Korean version shall prevail.
