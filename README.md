# Awesome Ethereum Classic ![Awesome](https://raw.githubusercontent.com/sindresorhus/awesome/9d1890e8baab141df4f6c271b414dc941d37ebae/media/badge-flat2.svg)

An awesome list of resources for the Ethereum Classic (ETC) project. This is an open-source project contributed by the ETC community. See [contribute](#contribute) to get started supporting this project.

# Overview & History

- [ETC Asset Profile](https://messari.io/asset/ethereum-classic/profile) - Asset profile provided by Messari.
- [ETC Declaration of Independance](https://ethereumclassic.org/ETC_Declaration_of_Independence.pdf)
- [ETC Timeline](http://ethereumclassic.org/knowledge/roadmap)

## ETC EVM Networks

| Name | Network | Chain ID  | Concensus | Clients |
| --- | :---: | :---: | :---: | :---: |
| Ethereum Classic | MainNet | 61 | PoW | Core-geth, Besu |
| Astor | TestNet | 212 | PoW | Besu |
| Kotti | TestNet | 6 | PoA | Core-geth, Besu |
| Mordor | TestNet | 63 | PoW | Core-geth, Besu |

## Core Organizations

- [ETC Cooperative](https://etccooperative.org/)
- [ETC Core](https://etccore.io/)

# Public Utilities

## Network Public Utilities

- Mainnet
  - Block Explorer
    - [BlockScout](https://blockscout.com/etc/mainnet/)
    - [Emerald Receipt](https://receipt.emeraldpay.io/)
    - [ETCBlockExplorer](https://etcblockexplorer.com/)
    - [Expedition](https://expedition.dev/?network=mainnet)
  - Metrics/ Dashboards
    - [Besu Grafana Dashboard](https://grafana.mariomichel.com/d/5S-6O8VZk/hyperledger-besu-node-at-ethereum-classic)
- Astor
  - Faucet
    - [Astor Faucet](http://astor.tmio.io:8080/)
- Kotti
  - Block Explorer
    - [Blockscout](https://blockscout.com/etc/kotti/)
  - Faucet
    - [Kotti Authenticated Faucet](https://kottifaucet.me/)
- Mordor
  - Block Explorer
    - [Blockscout](https://blockscout.com/etc/mordor/)
  - Faucet
    - [Mordor Authenticated Faucet](https://mordor.canhaz.net/)

# Developers

## Clients

- [Core-geth](http://core-geth.org/) - An ETC protocol providing clients written in Go.
- [Hyperledger Besu](https://besu.hyperledger.org/en/stable/) - An ETC protocol providing client written in Java.

## Infrastructure Providers
- [Bloq Cloud](https://bloq.cloud/) - BloqCloud delivers highly-optimized, always available access to blockchain networks.
- [Ethercluster](https://www.ethercluster.com/) (free) - Ethercluster is an open-source Infura-like alernative based on GKE. 
- [Rivet](https://rivet.cloud/) - Cloud-based Ethereum APIs that truly just work.

## Tooling

- [BUIDL IDE](https://buidl.secondstate.io/etc) - Second State BUIDL IDE is a web-based IDE that requires no software download or install. It provides a one-stop development and deployment environment for smart contract and dapp developers.
- [Dappkit](https://dappkit.io/) - A ledger-agnostic, high-performance infrastructure and libraries for developers to build and scale decentralized applications. In short, collaborative Firebase for Dapps.
- [Embark Framework](https://framework.embarklabs.io/) - Framework for serverless Decentralized Applications using Ethereum, IPFS and other platforms.
- [Emerald Platform](https://github.com/ETCDEVTeam/emerald-platform) - Platform for building Dapps for ETC blockchain.
- [ESerialize](https://eserialize.com/?input=string&output=hex) - The goal of this module is to provide easy functions to serialize and deserialize data for the Ethereum Stack.
- [Ethereum JSON-RPC API](https://github.com/etclabscore/ethereum-json-rpc-specification) - A specification of JSON-RPC methods that an EVM-based blockchain client must implement.
- [Eth Fiddle](https://ethfiddle.com/) - Online editor for smart contracts.
- [EVM-LLVM](https://github.com/etclabscore/evm_llvm) - Not only can developers use a large scope of programming languages (Rust for smart contracts!) other than Solidity to target the Ethereum Virtual Machine (EVM), they can also immediately benefit from various development tools built around LLVM infrastructure.
- [Ganache](https://www.trufflesuite.com/ganache) - Personal Ethereum blockchain to run tests.
- [Jade Suite](https://jade.builders/) - The Jade suite of tools empowers developers to create peer-to-peer decentralized applications on top of EVM-based blockchains like Ethereum Classic.
- [Mythx](https://mythx.io/) - MythX is the premier security analysis service for Ethereum smart contracts. Our mission is to ensure development teams avoid costly errors and make Ethereum a more secure and trustworthy platform.
- [Open-RPC](https://open-rpc.org/) - The OpenRPC Specification defines a standard, programming language-agnostic interface description for JSON-RPC 2.0 APIs.
- [OpenZeppelin](https://openzeppelin.org/) - Battle-tested framework of secure, reusable smart contracts.
- [Quorum](https://www.goquorum.com/) - Quorum is an open source blockchain platform that combines the innovation of the public Ethereum community with enhancements to support enterprise needs.
- [Remix Online IDE](https://remix.ethereum.org/) - A useful in-browser IDE that can compile and publish smart contracts to various Ethereum networks. Includes a linter.
- [Signatory](https://signatory.dev/) - An offline transaction and message signer for the Ethereum Stack.
- [SOLL](https://github.com/second-state/soll) - The LLVM compiler is finally coming to Solidity. With it, we can easily create smart contracts across multiple blockchain VMs. The EVM on Ethereum Classic and ETH 2.0's eWASM are among the first we support.
- [Sputnikvm](https://github.com/ETCDEVTeam/sputnikvm) - SputnikVM is an open source standalone implementation of Ethereum Virtual Machine (EVM). It aims to be an efficient, pluggable virtual machine for different Ethereum-based blockchains.
- [Truffle Suite](https://www.trufflesuite.com/) - A world class development environment, testing framework and asset pipeline for blockchains using the Ethereum Virtual Machine (EVM), aiming to make life as a developer easier.

## EVM Interoperability Projects
- [BTC-to-wBTC](https://wbtc.network/) - Wrapped Bitcoin delivers the power of Bitcoin with the flexibility of an ERC20 token. Bitcoin tokenized on EVMs.
- [ETC-to-wETC](https://wetc.app/) - The Ethereum Classic Bridge connects ETC-to-ETH, where ETC is available as wETC on the Ethereum (ETH) chain.
- [EVM-to-BNC Bridge](https://docs.tokenbridge.net/eth-bnc-bridge/about-eth-bnc-bridge) - The EVM-to-BNC bridge combines the TokenBridge approach with a TSS to approve relay operations and facilitate asset transfer between an EVM chain and the Binance chain.
- [Token Bridge](https://docs.tokenbridge.net/) - The TokenBridge allows users to transfer data (e.g. digital asset ownership information) between two chains in the Ethereum ecosystem. Cross-chain bridges provide fast and secure connections between blockchains, creating scalability and connection - interoperability - between Ethereum EVM networks.

## Tutorials

Step by step guides on using the Ethereum tech stack.

- [CryptoZombies](https://cryptozombies.io/) - Learn to Code Ethereum DApps By Building Your Own Game.
- [Hitchhikers Guide to Smart Contracts](https://blog.zeppelin.solutions/the-hitchhikers-guide-to-smart-contracts-in-ethereum-848f08001f05) - Build smart contracts on Ethereum using Truffle, testrpc and Solidity.
- [A 101 Noob Intro to Programming Smart Contracts on Ethereum](https://medium.com/@ConsenSys/a-101-noob-intro-to-programming-smart-contracts-on-ethereum-695d15c1dab4) - Smart contract tutorial with a focus on building up understanding before code.
- [Parity DApp Tutorial](https://wiki.parity.io/Dapp-Tutorial) - 10 part tutorial on how to write DApps.
- [Start Ethereum DApp Development Career](https://www.reddit.com/r/ethereum/comments/9h0w83/start_ethereum_dapp_development_career_ultimate/) - Informal guide to starting developing DApps.
- [Full Stack DApp Tutorial Series](https://kauri.io/collection/5b8e401ee727370001c942e3/full-stack-dapp-tutorial-series) - Full stack DApps using various frameworks.
- [Ethereum Builders Guide](https://ethereumbuilders.gitbooks.io/guide/content/en/index.html) - Gitbook for building on Ethereum that goes deeper into understanding technical functionality.
- [Learning Solidity Tutorial Series](https://karl.tech/learning-solidity-part-1-deploy-a-contract/) - Building smart contracts with Metamask and Remix IDE.
- [End to End DApp Tutorial](https://medium.com/@merunasgrincalaitis/the-ultimate-end-to-end-tutorial-to-create-and-deploy-a-fully-descentralized-dapp-in-ethereum-18f0cf6d7e0e) - Create a gambling DApp using Metamask, Truffle, Remix, React and IPFS.
- [Various Ethereum & Solidity Tutorials](https://www.codementor.io/learn/blockchain/solidity-tutorials) - How to create smart contracts, deploy your own DApps, create tokens, and more — from beginner to intermediate topics.

## Crowdfunding and freelance

- [GitCoin](https://gitcoin.co/) - Crowdfunding and Freelance Developers for Open Source Software Projects.

# User Showcase

- [Commonwealth](https://commonwealth.gg/) - A peer-to-peer savings fund that allows its users to own micro-equity and share fees from its use.
- [Grayscale® Ethereum Classic Trust](https://grayscale.co/ethereum-classic-trust/) - ETCG is solely and passively invested in Ethereum Classic, enabling investors to gain exposure to ETC in the form of a security while avoiding the challenges of buying, storing, and safekeeping ETC directly.

# Investors

## Exchanges

- [Binance](https://www.binance.com/en/trade/ETC_USDT)
- [Binance US](https://www.binance.us/en/trade/ETC_USD)
- [Bitfinex](https://www.bitfinex.com/t/ETC:USD)
- [Bithumb](https://www.bithumb.com/trade/order/ETCKRW)
- [Bittrex](https://bittrex.com/Market/Index?MarketName=USD-ETC)
- [Coinbase Pro](https://pro.coinbase.com/trade/ETC-USD)
- [eToro](https://www.etoro.com/discover/markets/cryptocurrencies/coins)
- [eToroX](https://www.etorox.com/exchange/etc/)
- [Gate](https://gate.io/trade/etc_usdt)
- [HitBTC](https://hitbtc.com/ETC-to-USDT)
- [Huobi Global](https://www.huobi.com/en-us/exchange/etc_usdt/)
- [Huobi Korea](https://www.huobi.co.kr/en-US/exchange/etc_usdt/)
- [Kraken](https://trade.kraken.com/markets/kraken/etc/usd)
- [Kucoin](https://www.kucoin.com/trade/ETC-USDT)
- [OKCoin](https://www.okcoin.com/spot/trade#product=etc_usd)
- [OKEx](https://www.okex.com/market?product=etc_usdt)
- [OKEx Korea](https://okex.co.kr/kr/view/trade/order)
- [Poloniex](https://poloniex.com/exchange#usdt_etc)
- [Upbit](https://upbit.com/exchange?code=CRIX.UPBIT.KRW-ETC)
- [Yobit](https://yobit.net/en/trade/ETC/BTC)

## Instant Exchanges

- [ABRA](https://www.abra.com/)
- [ALFACashier](https://www.alfacashier.com/)
- [AtomicWallet](https://atomicwallet.io)
- [ChangeAngel](https://www.changeangel.io/)
- [Changelly](https://changelly.com/)
- [ChangeNOW](https://changenow.io/)
- [CoinSwitch](https://coinswitch.co/)
- [Coinveer](https://coinveer.com/)
- [Edge](https://edge.app/)
- [Exodus](https://www.exodus.io/)
- [SecureShift](https://secureshift.io/)
- [Exolix](https://exolix.com/)
- [FixedFloat](https://fixedfloat.com/)
- [GoDex](https://godex.io/)
- [Infinito Wallet](https://www.infinitowallet.io/)
- [InstaEx](https://instaex.io/)
- [SimpleSwap](https://simpleswap.io/coins/ethereum-classic)
- [StealthEx](https://stealthex.io/)
- [SwapSwop](https://swapswop.io/)
- [Swapzone](https://swapzone.io/?to=btc&from=etc)
- [Switchain](https://www.switchain.com)
- [Voyager](https://www.investvoyager.com/blog/how-to-buy-ethereum-classic/)
- [XChange](https://www.xchange.me/)

## Payment Processors

- [AnyCoinDirect](https://anycoindirect.eu/en/buy-ethereum-classic)
- [Bit4Sale](https://bit4.sale/)
- [Bitladon](https://www.bitladon.com/ethereum-classic)
- [CoinDirect](https://www.coindirect.com/)
- [CoinGate](https://coingate.com/)
- [Coinmerce](https://coinmerce.io/)
- [CoinPayments](https://www.coinpayments.net/)
- [Cryptomate](https://cryptomate.co.uk/buy-ethereum-classic/)
- [Cryptonator Merchant](https://www.cryptonator.com/merchant/)
- [Fud Desk](https://fuddesk.com/buy-crypto)
- [LiteBit](https://www.litebit.eu/en/buy/ethereumclassic#rate-tile-ethereumclassic)
- [NOWPayments](https://nowpayments.io/)
- [Paxful](https://paxful.com/sell-bitcoin/ethereum-classic-etc)
- [RoundlyX](https://www.roundlyx.com/)
- [Utrust](https://utrust.com/)

## Portfolio Trackers

- [AltPocket](https://altpocket.io/)
- [Blockfolio](https://blockfolio.com/)
- [Delta](https://delta.app/)
- [GEM](https://gem.co/)
- [Coinfolio](https://coin-folio.com/)
- [CoinFYI](https://coin.fyi/coins/ethereum-classic)
- [CoinStats](https://coinstats.app/)
- [CoinTracking](https://cointracking.info/)
## Screeners

- [CNBC](https://www.cnbc.com/quotes/?symbol=ETCG&qsearchterm=ethereum)
- [CoinCodex](https://coincodex.com/crypto/ethereum-classic/)
- [CoinGecko](https://www.coingecko.com/en/coins/ethereum-classic)
- [CoinLib](https://coinlib.io/coin/ETC/Ethereum+Classic)
- [CoinRanking](https://coinranking.com/coin/hnfQfsYfeIGUQ+ethereumclassic-etc)
- [CryptoRating](https://www.crypto-rating.com/price-prediction/etc/)
- [CryptoReport](https://cryptoreport.com/ethereum-classic/ETC)
- [CryptoCompare](https://www.cryptocompare.com/coins/etc/overview/BTC)
- [CryptocurrencyChart](https://www.cryptocurrencychart.com/coin/ETC)
- [CryptocurrencyLivePrices](https://cryptocurrencyliveprices.com/coin.php?id=Ethereum-Classic)
- [LiveCoinWatch](https://www.livecoinwatch.com/price/EthereumClassic-ETC)
- [MarketWatch](https://www.marketwatch.com/investing/cryptocurrency/etcusd?iso=kraken)
- [Messari](https://messari.io/asset/ethereum-classic)
- [Prices.org](https://prices.org/ethereumclassic/)
- [TradingView](https://www.tradingview.com/symbols/ETCUSD/)
- [WorldCoinIndex](https://www.worldcoinindex.com/coin/ethereumclassic)
- [Yahoo Finance](https://finance.yahoo.com/quote/ETC-USD?p=ETC-USD)

## News Aggregators

- [Blockfolio Signal](https://blockfolio.com/signal)
- [Bloomberg Crypto](https://www.bloomberg.com/topics/ethereum-classic)
- [Coinstats News](https://coinstats.app/en/news)
- [CryptoPanic](https://cryptopanic.com/news/ethereum-classic/)
- [Delta Direct](https://delta.app/en/direct)
- [TokenInsight](https://tokeninsight.com/tokenDetail?cid=2659)

### Dapp Lists

- [CoinCodex](https://coincodex.com/dapp-list/)
- [CryptoGround](https://www.cryptoground.com/dapp)
- [Dapp.com](https://www.dapp.com/ja/search)
- [DappDirect](https://dappdirect.net/)
- [DappRadar](https://dappradar.com/)
- [Dapp.Review](https://dapp.review/explore)
- [DappStatus](https://dappstatus.com/)
- [State of the Dapps](https://www.stateofthedapps.com/)

## Taxation Tools

- [Accointing](https://www.accointing.com/)
- [CoinTracker](https://www.cointracker.io/)
- [CoinTracking](https://cointracking.info/)
- [Koinly](https://koinly.io/)

# Wallets

- MyCrypto
- MetaMask
- MyEtherWallet
- Nifty Wallet

## Hardware Wallet

Hardware wallets are secure wallets designed for long term storage.

- [Bitski](https://www.bitski.com/)
- [Ellipal](https://www.ellipal.com/)
- [Ledger](https://shop.ledger.com/)
- [SafePal](https://www.safepal.io/)
- [Trezor](https://trezor.io/)

## Software Wallets

Software wallets are Desktop or Mobile devices designed for short-term storage.

- [Alpha Wallet](https://alphawallet.com/)
- [AToken](https://www.atoken.com/)
- [Atomic Wallet](https://atomicwallet.io/)
- [Button Wallet](https://buttonwallet.com/)
- [Citowise](https://citowise.com/)
- [Cobo](https://cobo.com/)
- [Coinbase Wallet](https://wallet.coinbase.com/)
- [Coinomi](https://www.coinomi.com/)
- [Cryptonator](https://www.cryptonator.com/)
- [Edge](https://edge.app/)
- [Emerald Wallet](https://emeraldpay.io/)
- [Ethos](https://www.ethos.io/universal-wallet/)
- [eToro Wallet](https://www.etorox.com/crypto-wallet/)
- [Exodus](https://www.exodus.io/)
- [Guarda](https://guarda.co/)
- [Infinito Wallet](https://www.infinitowallet.io/)
- [Jaxx](https://jaxx.io/)
- [Midas Protocol](https://midasprotocol.io/)
- [Ownbit](https://ownbit.io/)
- [Trust Wallet](https://trustwallet.com/)
- [Zelcore Wallet](https://zel.network/project/zelcore/)

## Metal Wallets

- [BillFodl](https://billfodl.com/)
- [Blockplate](https://www.blockplate.com/)
- [ColdTi](https://coldti.com/)
- [Crypto Key Stack](https://cryptokeystack.com/)
- [CRYPTOTAG](https://cryptotag.io/)
- [Hodlinox](https://hodlinox.com/)
- [Steely](https://thesteely.com/)
  
# Mining
## Mining Pools

- [Ethermine](https://etc.ethermine.org/)
- [Nanopool](https://etc.nanopool.org/)
- [Hiveon Pool](https://hiveon.net/)
- [MiningPoolHub](https://ethereum-classic.miningpoolhub.com/)
- [2Miners](https://2miners.com/etc-mining-pool)

See more mining pools: https://tinyurl.com/2xpd86p3
### Mining Software

- [NanoMiner](https://github.com/nanopool/nanominer/releases/tag/v1.12.0)
- [LolMiner](https://github.com/Lolliedieb/lolMiner-releases/releases/tag/1.12)
- [GMiner](https://github.com/develsoftware/GMinerRelease/releases/tag/2.30)
- [T-Rex](https://github.com/trexminer/T-Rex/releases/tag/0.18.8)
- [NBMiner](https://github.com/NebuTech/NBMiner/releases/tag/v33.4)
- [SRBMiner-Multi](https://github.com/doktor83/SRBMiner-Multi/releases/tag/0.5.6)
- [TeamRedMiner](https://github.com/todxx/teamredminer/releases/tag/0.7.18)
- [PhoenixMiner](https://github.com/ethash-community/ethash/releases/tag/5.3b)

### Mining Pool Software
- [Open ETC Pool](https://github.com/etclabscore/open-etc-pool)
- [Stand-alone `etchash` library (go)](https://github.com/etclabscore/go-etchash)

# Community

## Chat
- Discord: [ETC - Ethereum Classic](https://discord.gg/hQs894U)
- Telegram: [Arabic](https://t.me/EtherClassic_Ar), [China](https://t.me/etczh), [English](https://telegram.me/ethclassic), [English](https://t.me/etcchat), [Español](https://t.me/ethclassicesp), [German](https://t.me/EtherCalssic_de), [Italia](https://t.me/ETC_Italia), [Russia](https://telegram.me/etcrussia), [Russia](https://telegram.me/etcru), [Viet Nam](https://t.me/ETCVietnam)

### Forum
- Reddit: [r/EthereumClassic](https://www.reddit.com/r/EthereumClassic/)

### Podcasts
- [EVM61](https://www.youtube.com/playlist?list=PLiW3acHwcR6LAa_WS5sFWf1S_GquYVeJb)
- [Explore The Chain](https://www.youtube.com/playlist?list=PL8fotqNQa4-UGxH8rCqeHAtOG56OyhZGf)
- [Let's Talk ETC!](https://www.youtube.com/playlist?list=PLKO8sMfwkZQqGH3Ny2OJ_SRcAvSf_0gx5)

### Repository
- [Github](https://github.com/ethereumclassic)

### Twitter
- Twitter: [@eth_classic](https://twitter.com/eth_classic)
### Websites
- [EthereumClassic.org](https://ethereumclassic.org)
- Region Specific Sites: , [China](http://ethereumclassic.cn/)

# Education

## Papers
- [Ethereum Project White Paper](https://github.com/ethereumclassic/wiki/ethereum_white_paper.pdf) - Non-technical introductory description of the Ethereum project.
- [Ethereum Project Yellow Paper](https://github.com/ethereumclassic/wiki/ethereum_yellow_paper.pdf) - Technical description of the Ethereum project. Technically outdated, but interesting.

## Wiki
- [Ethereum Classic chain's Wiki (ETC)](https://github.com/ethereumclassic/wiki/wiki) - Ethereum Classic wiki covering all things related to Ethereum Classic. The go-to place for all things Ethereum Classic (ETC) chain.
- [Ethereum chain's Wiki (ETH)](https://github.com/ethereum/wiki/wiki) - Ethereum wiki covering all things related to Ethereum. The go-to place for all things Ethereum (ETH) chain.
- [Ethereum chain's Community Wiki (ETH)](https://eth.wiki/) - Ethereum's ETH community wiki. An alternative wiki for the Ethereum chain (ETH).

## Smart Contract Documentation
- [Solidity Documentation](https://solidity.readthedocs.io) - Programming language of choice for smart contracts.
- [Vyper Documentation](https://vyper.readthedocs.io/en/latest/index.html) - Experimental smart contract programming language intended to replace Solidity.

## Theory and Concepts
Learn about the theory behind the Ethereum project.
- [Ethereum Stack Exchange](https://ethereum.meta.stackexchange.com/questions/431/faq-frequently-asked-questions-and-reference-answers) - Question and answers about Ethereum.
- [Smart contract safety](https://github.com/ethereum/wiki/wiki/Safety) - Ethereum wiki on best practices for safety in smart contracts.
- [Accounts, Transactions, Gas, and Block Gas Limits in Ethereum](https://hudsonjameson.com/2017-06-27-accounts-transactions-gas-ethereum/) - Functional description of Ethereum accounts, gas and transactions.
- [Ethernaut Smart Contract Capture the Flag](https://ethernaut.zeppelin.solutions/) - Practice hacking Smart Contracts.
- [Ethereum Syllabus](https://novicedock.com/learn/cryptocurrency/ethereum) - Syllabus to learn Ethereum.
- [Cryptocurrency Security: University of Illinois 2016](http://soc1024.ece.illinois.edu/teaching/ece598am/fall2016/) - Cryptocurrency Security Course.
- [Stanford CS 251(p): Bitcoin and Crypto Currencies](https://crypto.stanford.edu/cs251_fall15/) - Stanford Bitcoin and Cryptocurrency Course.
- [Introduction to Digital Currencies: University of Nicosia](https://digitalcurrency.unic.ac.cy/free-introductory-mooc/) - Digital currency introductory MOOC.
- [Bitcoin and Blockchain Technology: Concordia University](https://users.encs.concordia.ca/~clark/courses/1703-6630/index.html) - Introduction to Bitcoin and blockchain technology MOOC.
- [Smart Contract Best Practices](https://consensys.github.io/smart-contract-best-practices/) - Security related best practices for smart contracts.
- [Low-Resource Eclipse Attacks on Ethereum’s Peer-to-Peer Network](https://www.cs.bu.edu/~goldbe/projects/eclipseEth.pdf)
- [The idea of Smart Contracts](https://web.archive.org/web/20020316215014/http://szabo.best.vwh.net/idea.html) - Nick Szabo's idea of smart contracts post from 1997.
- [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/en/bitcoin-paper) - Satoshi Nakamoto's original paper is still recommended reading for anyone studying how Bitcoin works.
- [Making Smart Contracts Smarter](https://eprint.iacr.org/2016/633.pdf) - Smart contract security attacks.
- [Ethereum Classic (ETC) Wiki Philosophy](https://github.com/ethereumclassic/wiki/Philosophy) - Some of the core philosophies of Ethereum's ETC chain.
- [Ethereum Classic (ETC) Improvement Proposals](https://ecips.ethereumclassic.org/) - Standards for the Ethereum's ETC platform, including core protocol specifications, client APIs, and contract standards (ECIPs).
- [Ethereum (ETH) Wiki Philosophy](https://github.com/ethereum/wiki/Philosophy) - Some of the core philosophies of Ethereum's ETH chain.
- [Ethereum(ETH) )Improvement Proposals](https://eips.ethereum.org/) - Standards for Ethereum's ETH platform, including core protocol specifications, client APIs, and contract standards (EIPS).
- [Understanding the DAO](https://www.coindesk.com/understanding-dao-hack-journalists)
- [The Ethereum Classic Declaration of Independence](https://github.com/ethereumclassic/wiki/wiki/The-Ethereum-Classic-Declaration-Of-Independence)
- [A Crypto-Decentralist Manifesto](https://ethereumclassic.org/blog/2016-07-11-manifesto/)
- [Phyro's Recap of ETC History](https://phyro.github.io/etc-history/)
- [Ethereum Classic Principles](https://etherplan.com/2019/08/14/ethereum-classic-principles/8575/)
- [Ethereum Classic Vision](https://etherplan.com/2019/08/14/ethereum-classic-vision/8595/)
- [Ethereum Classic Opportunities](https://etherplan.com/2019/08/14/ethereum-classic-opportunities/8614/)
- [Ethereum Classic vs Ethereum 2.0, What is the Difference?](https://etherplan.com/2019/07/23/ethereum-classic-vs-ethereum-2-0-what-is-the-difference/8425/)
- [Why Proof of Stake is Less Secure Than Proof of Work](https://etherplan.com/2019/10/07/why-proof-of-stake-is-less-secure-than-proof-of-work/9077/)
- [How to Have a Vision for Ethereum Classic Without Creating a Governance Orgy](https://etherplan.com/2019/07/22/how-to-have-a-vision-for-ethereum-classic-without-creating-a-governance-orgy/8359/)
- [The Ethereum Classic vs Ethereum 1.x Dichotomy](https://etherplan.com/2019/09/18/the-ethereum-classic-vs-ethereum-1-x-dichotomy/8752/)
- [Into the Ether with Ethereum Classic](https://grayscale.co/insights/into-the-ether-with-ethereum-classic/) - The Store of Value Commodity to Power the Internet of Things
- [What is Ethereum Classic (ETC)?](https://www.publish0x.com/the-crypto-enthusiast-blog-intro/what-is-ethereum-classic-etc-the-coin-that-got-away-beginner-xkzrzo) - A Beginner's Guide to the `The Coin that Got Away`

## Consensus Algorithms

- [Dagger Hashimoto](https://github.com/ethereum/wiki/wiki/Dagger-Hashimoto)
- [Clique](https://medium.com/@Destiner/clique-cross-client-proof-of-authority-algorithm-for-ethereum-8b2a135201d)
- [EtcHash](https://github.com/eth-classic/etchash) - 
- [EthHash](https://github.com/ethereum/wiki/wiki/Ethash) - 
- [Sha-3](https://csrc.nist.gov/projects/hash-functions/sha-3-project)

## Ethereum Project Protocols
Descriptions and implementations of Ethereum-related protocols.

### Swarm
- [Introduction to Swarm](https://swarm.ethereum.org/) - Swarm is a distributed storage platform and content distribution service.

### Whisper
- [Introduction to Whisper](https://github.com/ethereum/wiki/wiki/Whisper-pages) - A communication protocol for DApps to communicate with each other.

### zk-SNARKS
- [Introduction to zk-SNARKS with examples](https://media.consensys.net/introduction-to-zksnarks-with-examples-3283b554fc3b) - A practical overview of zk-SNARKS, verify knowledge of a secret without revealing it.
- [A practical beginner's guide to creating, proving, and verifying zkSNARKs](https://github.com/jstoxrocky/zksnarks_example) - Introduction to zk-SNARKS and implementation as a smart contract.
- [zk-SNARKS: Under the Hood](https://medium.com/@VitalikButerin/zk-snarks-under-the-hood-b33151a013f6) - Technical explanation of zk-SNARKS.
- [zk-SNARKs in a nutshell](https://blog.ethereum.org/2016/12/05/zksnarks-in-a-nutshell/) - Technical explanation of zk-SNARKS.
- [Practical zk-SNARKs for Ethereum EVM's](http://coders-errand.com/practical-zk-snarks-for-ethereum/) - A short and practical introduction to using zk-SNARKs.

## Token Bonding Curves (TBC)
- [Bonding Curves Explained](https://yos.io/2018/11/10/bonding-curves/) - Mathematically sound price-supply relationship curves., a thorough introduction to TBCs with code.
- [Token Bonding Curves in Practice](https://tokeneconomy.co/token-bonding-curves-in-practice-3eb904720cb8) - Exploring a universal distribution of IP via non-fungible tokens and curation markets.
- [Bonding Curve Playground](https://bondingplayground.netlify.com/) - An interactive bonding curve webapp.

# Ethereum Classic Media and Other Content
## Blogs, Mailing Lists, Newsletters
- [Etherplan](https://etherplan.com/) - Donald McIntyre's research, articles, & podcast about Ethereum Classic, Bitcoin, and decentralized applications.
- [Grayscale® Ethereum Classic Trust](https://grayscale.co/ethereum-classic-trust/) - Grayscale Ethereum Classic Trust enables investors to gain exposure to the price movement of ETC through a traditional investment vehicle, without the challenges of buying, storing, and safekeeping ETC.
- [Messari's Ethereum Classic News and Research](https://messari.io/asset/ethereum-classic/news) - Messari brings transparency to the cryptoeconomy. We want to help investors, regulators, and the public make sense of this revolutionary new asset class, and are building data tools that will drive informed decision making and investment.
- [Ethereum Classic Today](https://etc.today/) - A weekly summary of everything happening in ETCLand.
- [Week in Ethereum News](https://weekinethereumnews.com/) - A summary of everything happening in Ethereum each week.
- [Ethereum Worldwide Meetups](https://www.meetup.com/find/?allMeetups=false&keywords=ethereum) - Meet up with the local Ethereum community via meetup.com.
- [ETC Gifs](https://github.com/stevanlohja/ETC_Gifs) - Ethereum Classic social media meme repository
- [Coingecko Reports](https://reports.coingecko.com/all-reports) - high quality market reports with graph visuals.
- [Ethereum Classic Community Art](https://www.flickr.com/photos/ethereumclassic) - a collection of Ethereum Classic art.

## Books
- [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook) - A developers guide to the operation and use of the Ethereum project.
- [Introduction to Ethereum and Solidity](https://the-eye.eu/public/Books/qt.vidyagam.es/library/humble-bitcoin-bundle/Introducing%20Ethereum%20and%20Solidity_%20Foud%20Blockchain%20Programming%20for%20Beginners/Introducing%20Ethereum%20and%20Solidity_%20Foundatiin%20Programming%20for%20Beginners%20-%20Chris%20Dannen.pdf) - Learn Solidity development from concept to deployment.
- [Ethereum: Blockchains, Digital Assets, Smart Contracts, Decentralized Autonomous Organizations](https://www.goodreads.com/book/show/32762240-ethereum) - Learn about Ethereum (and blockchains) from an IBM blockchain liaison.

## Conferences
### ETC Summit 2017
  + [ETC Summit 2017 Hong Kong](https://etcsummit.com/2017-summit/): [Full Livestream - November, 2017](https://www.youtube.com/watch?v=vYvbzjETbxI&list=PL20HSZ6AK2yOrde28Pi_XCoaDWbahIhi0)

### ETC Summit 2018
  + [ETC Summit 2018 Seoul](https://etcsummit.com/2018-etc-summit/): [Full Livestream - September 12, 2018](https://youtu.be/81EjJ5-sTRg)

### ETC Summit 2019
  + [ETC Summit 2019 Vancouver](https://etcsummit.com/): [Full Day 1 - October 3rd, 2019](https://www.youtube.com/watch?v=Msi6EItbslk&list=PL20HSZ6AK2yOSOhBGFtLj6zPLkJEm_3FF&index=6)
    + [Opening Address](https://youtu.be/Msi6EItbslk?t=1655) by Bob Summerwill [@BobSummerwill](https://twitter.com/BobSummerwill), Executive Director of [ETC Cooperative](https://etccooperative.org/).
    + [The State of Ethereum Classic](https://youtu.be/Msi6EItbslk?t=3205) by Anthony Lusardi [@pyskell](https://twitter.com/pyskell), Former Executive Director of [ETC Cooperative](https://etccooperative.org/).
    + [Ethereum Classic Principles, Vision & Opportunity](https://youtu.be/Msi6EItbslk?t=3790) by Donald McIntyre [@MyEtherPlan](https://twitter.com/MyEtherplan), Researcher, Writer, & Podcaster [Etherplan](https://etherplan.com/).
    + [Atlantis Protocol Upgrade & The ETC Roadmap](https://youtu.be/Msi6EItbslk?t=5375) by Afri Schoeden [@a4fri](https://twitter.com/a4fri), [Ethereum Classic](https://ethereumclassic.org/) Core Developer.
    + [The Future of JSON-RPC Tooling](https://youtu.be/Msi6EItbslk?t=8290) by Shane Jonas [@shanejonas](https://twitter.com/shanejonas), Co-Lead Tooling Developer at [ETC Core](https://etccore.io/).
    + [Bridging the Decentralized Services Gap](https://youtu.be/Msi6EItbslk?t=8795) by Zane Starr [@zanecstarr](https://twitter.com/zanecstarr), Tooling Developer at [ETC Core](https://etccore.io/).
    + [Adding Merkle-Mountain-Ranges and Fly-Proofs to ETC](Link) by Zac Mitton [@VoltzRoad](https://twitter.com/VoltzRoad), Open Source Software Engineer at [Voltz Road](https://voltzroad.com/).
    + [Ethereum Classic's ECIP-1050: One Byte of Context](https://youtu.be/Msi6EItbslk?t=11350) by Brooklyn Zelenka [@expede](https://twitter.com/expede), Co-Founder/CTO of [FISSION](https://fission.codes/).
    + [The Year Ahead for Ethereum Classic Labs](https://youtu.be/Msi6EItbslk?t=15290) by Terry Culver [@realetclassic](https://twitter.com/realetclassic), CEO of [Ethereum Classic Labs](https://etclabs.org/) & [ETC Core](https://etccore.io/).
    + [Infrastructure for Decentralizing Distributed Networks](https://youtu.be/Msi6EItbslk?t=16455) by Aaron Lowry [@Aaron_Lowry](https://twitter.com/Aaron_Lowry), Co-Founder/CEO of [Ethernode](https://ethernode.io/).
    + [Radical Ideals: Experiments in Sustaining Open Source Software](https://youtu.be/Msi6EItbslk?t=18250) by Scott Moore [@notscottmoore](https://twitter.com/notscottmoore), Developer Relations Lead at [GitCoin](https://gitcoin.co/).
    + [POA Network: Development Tools in the ETC Ecosystem](https://youtu.be/Msi6EItbslk?t=21060) by Andrew Gross [@poanetwork](https://twitter.com/poanetwork), Technical Writer for [POA Network](https://www.poa.network/).
    + [State of the Ethereum Classic Testnets](https://youtu.be/Msi6EItbslk?t=23515) by Afri Schoeden [@a4fri](https://twitter.com/a4fri), [Ethereum Classic](https://ethereumclassic.org/) Core Developer.
    + [Metronome - First Cross-Chain #Cryptocurrency: Chain Hop From ETH to ETC](https://youtu.be/Msi6EItbslk?t=25170) by Manoj Patidar [@manojpatidarr](https://twitter.com/manojpatidarr), Principal Engineer at [Bloq](https://www.bloq.com/).
    + [Fireside Chat: Improving Investor Access to Ethereum Classic](https://youtu.be/Msi6EItbslk?t=26080) by Michael Sonnenshein [@Sonnenshein](https://twitter.com/Sonnenshein), Managing Director of [Grayscale](https://grayscale.co/).
    + [The Need for Cross Chain Collaboration](https://youtu.be/Msi6EItbslk?t=27755) by Aidan Hyman [@Aidan_IH](https://twitter.com/Aidan_IH), Co-Founder/CEO of [ChainSafe](https://chainsafe.io/).
    + [Developer Relations in Ethereum Classic](https://youtu.be/Msi6EItbslk?t=29190) by Yaz Khoury [@Yazanator](https://twitter.com/Yazanator), Director of Developer Relations at [ETC Cooperative](https://etccooperative.org/).
  + [ETC Summit 2019 Vancouver](https://etcsummit.com/): [Full Day 2 - October 4th, 2019](https://www.youtube.com/watch?v=TNsWR7jXllQ&list=PL20HSZ6AK2yOSOhBGFtLj6zPLkJEm_3FF&index=7)
    + [A New Open Source Deal for Web3](https://youtu.be/TNsWR7jXllQ?t=3240) by Boris Mann [@bmann](https://twitter.com/bmann), Co-Founder of [FISSION](https://fission.codes/).
    + [Positive Sum Games Between Ethereum & Ethereum Classic](https://youtu.be/TNsWR7jXllQ?t=5945) by Virgil Griffith [@virgilgr](https://twitter.com/virgilgr), Special Projects at the [Ethereum Foundation](https://ethereum.org/).
    + [A Peripheral Observer and Fan's View of Ethereum Classic]() by Sunny Aggarwal [@sunnya97](https://twitter.com/sunnya97), Researcher & Core Dev at [Tendermint](https://tendermint.com/) & [Cosmos](https://cosmos.network/).
    + [Is Open Source Software Immortal?](https://youtu.be/TNsWR7jXllQ?t=9560) by Zachary Belford [@belfordz](https://twitter.com/belfordz), Co-Lead Tooling Developer at [ETC Core](https://etccore.io/).
    + [Merging Blockchains: A Technical Perspective](https://youtu.be/TNsWR7jXllQ?t=11350) by Wei Tang [@sorpaas](https://twitter.com/sorpaas), Core Developer at [Parity](https://www.parity.io/).
    + [Ethereum Classic's EVM LLVM Project](https://youtu.be/TNsWR7jXllQ?t=12685) by Alan Li [@etc_core](https://twitter.com/etc_core), Lead Compiler Engineer at [ETC Core](https://etccore.io/).
    + [ECIP-1049: Why Ethereum Classic Should Adopt SHA3 Proof of Work](https://youtu.be/TNsWR7jXllQ?t=15310) by Alex Tsankov [@antsankov](https://twitter.com/antsankov), Open Source Developer at [Block Reaction](https://blockreaction.nyc/).
    + [Building Trust as a Miner or Miner-Maker](https://youtu.be/TNsWR7jXllQ?t=17315) by Nishant Sharma [@nishantsharma87](https://twitter.com/nishantsharma87), PR & Community Relations at [Bitmain](https://www.bitmain.com/).
    + [Ethereum Classic Ethash ASICs](https://youtu.be/TNsWR7jXllQ?t=18440) by Werner Almesberger [@LinzhiCorp](https://twitter.com/LinzhiCorp), System Architect at [Linzhi](https://linzhi.io/).
    + [ETC Summit Platform Panel: Afri Schoedon, Shane Jonas, Wei Tang, Zachary Belford, Zachary Mitton](https://youtu.be/TNsWR7jXllQ?t=23810) Moderated by Yaz Khoury [@Yazanator](https://twitter.com/Yazanator), Director of Developer Relations at [ETC Cooperative](https://etccooperative.org/).
    + [ETC Summit Community Panel: Chelsea Palmer, Donald McIntyre, Kevin Lord, Terry Culver, Yaz Khoury](https://youtu.be/TNsWR7jXllQ?t=25530) Moderated by Bob Summerwill [@BobSummerwill](https://twitter.com/BobSummerwill), Executive Director of [ETC Cooperative](https://etccooperative.org/).
    + ["Capture" Was Already Always Happening: The Complexity of Power in Blockchain Ecosystems](https://youtu.be/TNsWR7jXllQ?t=27480) by Chelsea Palmer [@chiselinc](https://twitter.com/chiselinc), Organizer of [DogeCon](http://www.dogecon.lol/).
    + [ETC Summit 2019: Closing Keynote](https://youtu.be/TNsWR7jXllQ?t=29745) by Charles Hoskinson [@IOHK_Charles](https://twitter.com/IOHK_Charles), Co-Founder/CEO of [IOHK](https://iohk.io/) & Co-Founder of the Ethereum Project.

## Crypto Podcasts
- [CryptoBasic](https://www.cryptobasicpodcast.com/episodes)
- [Epicenter](https://www.youtube.com/user/epicenterbtc/playlists)
- [EVM61](https://www.youtube.com/playlist?list=PLiW3acHwcR6LAa_WS5sFWf1S_GquYVeJb)
- [Explore The Chain](https://www.youtube.com/playlist?list=PL8fotqNQa4-UGxH8rCqeHAtOG56OyhZGf)
- [Fintech Legal](https://fintechlegal.fireside.fm/episodes)
- [Into the Ether](https://podcast.ethhub.io/)
- [Let's Talk ETC!](https://www.youtube.com/playlist?list=PLKO8sMfwkZQqGH3Ny2OJ_SRcAvSf_0gx5)
- [Programming Throwdown](https://www.programmingthrowdown.com/)
- [Software Engineering Daily - Blockchain](https://softwareengineeringdaily.com/category/blockchain/)
- [Software Engineering Radio](https://www.se-radio.net/)
- [This Week in Crypto](https://thisweekincrypto.co/)
- [Unchained](https://unchainedpodcast.com/)
- [Zero Knowledge](https://www.zeroknowledge.fm/)

## Videos
- [Ethereum Classic Explained](https://youtu.be/wOxwuoJaJXc) - 2016
- [Ethereum vs Ethereum Classic](https://youtu.be/IOuEgLKqqjE) - 2018
- [Ethereum Classic: Complete Review of ETC](https://youtu.be/xcenZlBdmzM) - 2019
- [Ethereum Explained (22:00)](https://www.youtube.com/watch?v=-_Qs0XdPpw8) - Introductory explanation to the Ethereum platform.
- [A Guide to Building Your First Decentralized Application (37:00)](https://www.youtube.com/watch?v=gSQXq2_j-mw)
- [Ethereum YouTube Channel](https://www.youtube.com/user/ethereumproject) - Mostly older videos of Devcon 1 and before.
- [Ethereum Foundation YouTube Channel](https://www.youtube.com/channel/UCNOfzGXD_C9YMYmnefmPH0g) - Most up to date events and streams including the Ethereum Devcon conferences and dev meetings.
- [Unstoppable Code: The Difference Between Can't and Won't](https://youtu.be/Q6euy5W1js4) -  In this talk, Andreas discusses what is interesting about both Bitcoin and Ethereum: unstoppable code. He looks at cryptography and decentralized systems as defensive mechanisms to assert and enforce our human rights, and the effect of the Silk Road on the public's perception of cryptocurrencies. He also warns that the Ethereum community will soon need to reconcile diverse ethical codes and legal jurisdictions, and make a decision about whether they will build "won't" or "can't" governance systems. What is the unstoppable code worth running?
# Contribute

To contribute to this document, simply submit an [issue](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/working-with-your-remote-repository-on-github-or-github-enterprise/creating-an-issue-or-pull-request) or [pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) to the `feature` branch and the maintainers will review. See the [Contributing](Contributing.md) guide for additional information.

# License

CCO
