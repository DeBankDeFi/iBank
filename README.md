# iBank -『EOS余额宝』理财产品

### 产品简介

『iBank』是EOS生态中借贷撮合行业的领导者，由国内顶级的DApp开发团队DappPub研发推出。产品核心基于『用户抵押EOS代币换取主网CPU使用时间』的功能，面向EOS代币长期持有用户以及短期EOS租赁用户，为EOS借贷双方提供最为安全快速的借贷撮合服务。

面向EOS代币长期持有用户，iBank提供『EOS余额宝』。这是一款链上活期理财产品，也是目前市场上唯一能够以活期形式灵活稳健地为EOS代币持有者提供资产增值的服务。该产品具有实时起息、实时结算、免费赎回、数据上链、公开透明等特点，并已与多款主流钱包及EOS节点共同多签以保障资产安全。无论是钱包还是交易所账户中闲置的EOS，用户都可以放心地将它们存储在iBank风控下的智能合约组中。

同时，面向需要CPU资源的短期EOS租户，iBank提供『资源租赁』产品，借助自主研发的高效资源调度模型，对智能合约中所存储的EOS进行循环利用，在主网上为短期EOS租户进行有偿CPU代抵押操作来获取收益，并最终将这些收益分配给『EOS余额宝』的储户。

------

### 活期理财，即刻起息

随着EOS生态的发展，EOS有限的主网资源将会变得越来越稀缺，主网的CPU使用成本也会更昂贵。很多开发者和游戏玩家经常在短时间内爆发出大量计算需求。与此同时，很多持币者也想要通过出租自己持有的EOS来获利。iBank作为EOS借贷撮合平台，面向EOS代币长期持有者和短期EOS租赁用户，提供安全快速的撮合服务，采用智能合约进行代抵押操作，降低了市场对接成本。

不同于以往的定期理财产品，『EOS余额宝』给用户提供了一套全新的活期理财解决方案，以满足用户随需多变的使用需求。当用户将EOS转入iBank智能合约之后即刻起息，每当『租赁资源』端有一笔新的CPU代抵押订单成交时，储户的EOS余额宝账户余额都会实时结算收益。

转入：免费，最小转入额为 500 EOS。

转出：免费，单次转出限额 20,000 EOS。受[EOS抵押系统](https://github.com/EOSIO/eos/tree/master/contracts/eosio.system)设计所限，提现操作需三天后到账。同时为了进一步提升用户体验，iBank目前提供『立即转出通道』，先行垫付用户的提现额度（无转出限额，T+0），费率锚定CPU市场3天EOS租赁市场价。

------

### 高效理财，稳健复利

iBank『资源租赁』端由EOS Bank、EOS Cloud、CPU一元租赁等渠道方提供租赁业务支持。

每当iBank的渠道方收到任意一笔资源租赁订单后，将会自动提取iBank的智能合约中的资金来完成租赁，与此同时，收到的利息也将会立刻被记账在每一位储户的EOS余额宝账户中。通过观察您的iBank账户，您会发现每隔几分钟，您的存款利息将会慢慢增加。每一笔利息都是真实租单提供的利息收入，我们根据您的存款占据总存款的份额来平均分配每一份租单收入。

由于CPU租赁市场的需求是在不断变化的，特别是DApp市场的火爆会导致CPU资源的异常紧张，iBank则会根据借贷两端的实际供需制定动态的定价策略。同时每一份新租单的收益也会立即进入资源池并等待智能合约的再次调度以产生高效的复利收益。『iBank借助自主研发的高效资源调度模型，对智能合约中所存储的EOS进行24x7不间断循环调用，将储户的每一份资产都进行充分地利用，以期给用户带来最高效的收益。

在iBank高效的资源调度模型下，CPU峰时7日年化一度高达15%+。同时，EOS余额宝』也是为『懒人』投资者打造的高效理财解决方案，智能合约封装了所有繁琐的技术细节，用户也无需关心多次租单之间的衔接与定价变化。

iBank现已登陆多款主流EOS移动钱包 (TokenPocket, MathWallet, MEET.ONE, imToken, PocketEos, MORE.TOP,  SeCrypto, EOS Live)。用户可在以上钱包DApp页面内搜索『iBank』进行访问，也可直接通过Chrome / Firefox桌面浏览器（需安装Scatter钱包插件）访问: https://ibankeos.io

------

### 链上理财，公开透明

存储在iBank智能合约中的EOS 100%全部用来抵押EOS的主网资源（CPU/NET），仅仅执行『delegatebw』抵押，没有『transfer』和『sent』资产，不存在擅自挪用用户资产的可能。借助区块链技术所提供的公开透明的分布式账本，每位用户都可以参与到iBank智能合约的审计过程中来。iBank所有的每一笔资金使用及对应的CPU租赁订单都在EOS主网上公开可查，避免了以往传统借贷市场中资金用途不明情况的发生。

iBank由国内顶级的DApp开发团队DappPub研发推出，作为行业领导者，iBank已与多个EOS节点（EOS CANNON, BlockGo, EOS ASIA）及EOS钱包（Oracle Chain, Token Pocket, Math Wallet）达成『多签合作伙伴』关系。iBank募集到的EOS都实时存放在iBank的仓库合约（[bankreserves](https://eosq.app/account/bankreserves)）中，并由DappPub与多签合作伙伴共同对合约进行多重签名操作以提供安全审核来保障客户资产的绝对安全。对该资金池账户的任何操作都需要其他多签伙伴一起确认才可以触发，这就保证了该合约中存储资金不受单独任意一方控制。

![image-20181228193559320](https://i.loli.net/2018/12/29/5c273f5101abb.png)

------

### 安全理财，风控严谨

我们的合约经过社区审计确保安全，同时对资金池帐号和合约账号做了完整的隔离架构，进一步保障用户资金安全。iBank为了资产安全，选择暂不开放合约源码。仓库合约的调用被严格限制在储户表内部，不能绕开储户表提款。

iBank的安全问题需要从整体的架构设计出发，尽可能隔离各业务模块间的安全问题，并在模块内尽所有可能将其解决好。我们将整个DApp以业务为界拆分成三个部分：储蓄产品、资金管理和资源租赁。然后，我们针对这三部分业务拆分出三个合约，分别进行相关业务的处理。储蓄产品由bankcoinfund进行处理，资金管理由bankreserves合约进行，资源租赁则由cpubankstake来进行处理。

储蓄合约在整个DApp中主要负责用户资金转入、转出以及利润的分配问题。这中间最重要的就是转入过程中，可能出现的假币、假通知等攻击方式对平台造成的损失。针对此类问题，我们完整的调研了整个EOS的转账机制，并针对转账过程中可能存在的所有风险点进行了预防和处理。而用户转出的过程中，对比较容易出现越权赎回和溢出攻击等问题进行了针对性的防范。同时资金管理合约中对外只提供一个租赁接口，该接口可以给指定的账号抵押资源，但抵押时EOS的所有权依然在资金池账号的管理下，永远不会出现EOS丢失的情况。

所以，通过对资金管理合约的多签和接口权限控制，保障了储户的资金不会发生丢失。除非节点、钱包与iBank一起同谋，否任何人无法卷款跑路，同时规避了资金被盗的风险和团队的道德风险。

资源租赁合约主要是进行租赁费用的收取以及利润的分配，主要的工作在于把费用和利润计算清楚，保障储户的利益不受损失。

拆分合约的根本原因是为了保障整个DApp的安全。经过拆分后，各合约相互之间解耦，各自的逻辑更加聚焦，也就更不容易出现因逻辑漏洞而被攻击。最后也因为进行了合约拆分，各自的业务特点所遇到的安全问题都可以得到最大化的解决。

------

### 常见问题：

- Q：提款三天到账和立刻提款有什么分别？
  A：由于EOS的设定，赎回资源需要3天时间，如果你现在发送提款命令，选择三天到账，那么你将不产生利息损失。然而当你选择立即提款模式的时候，实际上你存入的资产被抵押出去了，这需要我们提供资金垫付完成你的立即提款操作，所以他收取0.49%的手续费。我们如此设计是为了解决以下情况：如果一个人先存款1万币，然后立刻从CPU租赁市场租赁1万币，然后再次选择立即提取iBank的存款，那么他将会自己收到自己的租赁利息，这对于其他租赁客户来说，是一种不公平的行为。
- Q：为什么余额宝理财的利率是浮动的？
  A：就像传统的银行一样，假设银行的名义利率固定在6%，银行有100万币，那么当银行租赁出去50万币的时候，对于100万币来说，实际收到的利率仅仅是3%，也就是余额宝理财的收益率是挂钩CPU租赁市场的整体出租率。同时，随着EOS租赁市场的成熟，价格战在所难免。我们时刻关注租赁市场的变化，采取灵活的市场定价策略保持收益的均衡性。
- Q：你们应该努力让收益率上涨。
  A：这确实是我们努力的目标，iBank的收益率挂钩CPU租赁市场的出租率，但我们也会尝试使用“余额宝理财额度限制”来拉升理财的收益率。但是，出租率和储蓄额度是一个跷跷板的关系，所以，我们一直在优化我们的金融模型，以期在保持资金池稳定的情况下最大化提高理财的收益率。
- Q：我们会亏本吗？
  A：在极端的情况下，租赁也不会亏本，因为iBank这种理财模型是“租单分红”，也即每当CPU租赁市场收到租单，iBank立刻分红记账，它只有上涨和缓慢上涨，永远不会出现负收益。除非一种情况，你存款不足三天而又选择立刻提款，这将会收取0.49%的立即提款手续费。
- Q：与其他理财产品相比，iBank的优势是什么？
  A：当EOS币价下跌的时候，在iBank的存款你可以选择立刻提款以降低风险，而不会出现抵押给别人7天无法赎回的问题。相遇于24小时EOS币价下跌10%来说，0.49%的立即提款手续费不值一提，同时你的存款还拿到了利息早已覆盖这个成本。
- Q：iBank的余额宝会发生挤兑吗？我的资产能不能保证提取顺利？
  A：iBank拥有50万EOS币的底仓，我们深耕EOS生态，并不卖出自己拥有的EOS币，iBank资金池仅仅用于抵押操作，所有储户100%提取存款，也不会发生挤兑。
- Q：REX如果上线了，将会有什么影响？
  A：REX是面向开发者的资源租赁系统，他并不支持我们目前的超级短租业务，REX不支持常见的24小时租赁，72小时租赁等。租赁市场拥有很多个性化的需求，并非REX可以全部占据。

------

### 联系我们

官方网址：https://ibankeos.io

英文电报群：https://t.me/DappPub

中文电报群：https://t.me/DappPubCN

官方微信群: 	添加微信号 warrior404

------



![iBank_hz_vault](https://i.loli.net/2018/12/29/5c273b9d60283.jpeg)
