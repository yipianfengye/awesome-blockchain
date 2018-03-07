## awesome-blockchain

> 本文提出了一种完全通过点对点技术实现的电子现金系统，它使得在线支付能够直接由一方发起并支付给另外一方，中间不需要通过任何的金融机构。虽然数字签名（Digital signatures）部分解决了这个问题，但是如果仍然需要第三方的支持才能防止双重支付（double-spending）的话，那么这种系统也就失去了存在的价值。我们(we)在此提出一种解决方案，使现金系统在点对点的环境下运行，并防止双重支付问题。该网络通过随机散列（hashing）对全部交易加上时间戳（timestamps），将它们合并入一个不断延伸的基于随机散列的工作量证明（proof-of-work）的链条作为交易记录，除非重新完成全部的工作量证明，形成的交易记录将不可更改。最长的链条不仅将作为被观察到的事件序列（sequence）的证明，而且被看做是来自CPU计算能力最大的池（pool）。只要大多数的CPU计算能力都没有打算合作起来对全网进行攻击，那么诚实的节点将会生成最长的、超过攻击者的链条。这个系统本身需要的基础设施非常少。信息尽最大努力在全网传播即可，节点(nodes)可以随时离开和重新加入网络，并将最长的工作量证明链条作为在该节点离线期间发生的交易的证明 

以上是比特币白皮书中的摘要，希望大家通过摘要对比特币(btc)有一个基本的认识，并以此为起点开始学习比特币，学习区块链，学习以太坊，学习区块链2.0，学习智能合约等知识。本项目主要用于维护关于区块链中的各种知识点，欢迎大家一起维护。

想要学习区块链技术或者是为本项目贡献文档的可加入QQ群：<a href="#">727407003</a>


### <a href="#">目录</a>

* <a href="#whitePaper">白皮书</a>
 
* <a href="#aboutbtc">关于比特币</a>

* <a href="#aboutblockchain">关于区块链</a>

* <a href="#abouteth">关于以太坊</a>

* <a href="#course">热门教程</a>

* <a href="#project">项目源码</a>

* <a href="#sdk">SDK工具包</a>

* <a href="#material">技术文档</a>

* <a href="#datum">资料文档</a>

* <a href="#blockchainbrower">区块链浏览器</a>

* <a href="#wallet">Wallet钱包</a>

* <a href="#currency">虚拟币种</a>

* <a href="#website">交易网站</a>

* <a href="#webapi">交易API</a>

</br>

******

</br>

### <a name="whitePaper">白皮书</a>

* [比特币白皮书](http://www.8btc.com/wiki/bitcoin-a-peer-to-peer-electronic-cash-system)

* [以太坊白皮书](http://ethfans.org/posts/ethereum-whitepaper)

* [EOS白皮书](https://github.com/EOSIO/Documentation/blob/master/TechnicalWhitePaper.md/)

* [瑞波币白皮书](https://ripple.com/files/ripple_consensus_whitepaper.pdf)

* [艾达币白皮书](https://www.cardanohub.org/zh/academic-papers-3/)

* [小蚁白皮书](https://github.com/AntShares/AntShares/wiki/Whitepaper-1.1)

* [埃欧塔白皮书](https://iota.org/IOTA_Whitepaper.pdf)   

* [波场白皮书](https://dn-peiwo-web.qbox.me/Tron-Whitepaper-0831-V17.pdf) 

* [以太经典白皮书](https://ethereumclassic.github.io/assets/etc-thesis.pdf)

* [腾讯区块链白皮书](http://www.cbdio.com/BigData/2017-04/25/content_5503014.htm)

* [更多白皮书......](https://github.com/yipianfengye/awesome-blockchain/blob/master/WHITE_PAPER.md)


</br>

******

</br>

### <a name="aboutbtc">关于比特币</a>

* [精通比特币](http://book.8btc.com/books/1/master_bitcoin/_book/)

* [比特币块链和挖矿原理](http://www.8btc.com/bitcoin_block_chain)

</br>

******

</br>

### <a name="aboutblockchain">关于区块链</a>

* [理解区块链](http://blog.csdn.net/csolo/article/details/52858236)

* [简单介绍什么是区块链](https://zhuanlan.zhihu.com/p/22228902)

* [一文看懂区块链架构设计](http://www.8btc.com/ebook-blockchain)


</br>

******

</br>

### <a name="abouteth">关于以太坊</a>

* [以太坊设计原理](http://ethfans.org/posts/510)

* [以太坊代码剖析](http://ethfans.org/topics/227)

* [以太坊源码分析](http://www.cnblogs.com/baizx/category/1011749.html)


</br>

******

</br>

### <a name="course">热门教程</a>

* [以太坊从零开始学习](https://www.jianshu.com/p/220130b39e22)

* [以太坊入门经验](http://me.tryblockchain.org/getting-up-to-speed-on-ethereum.html) 

* [以太坊智能合约之菜鸟教程](http://ethfans.org/posts/101-noob-intro)


</br>

******

</br>

### <a name="project">项目源码</a>

* [比特币源码](https://github.com/fkysly/bitcoin0.1.0)

* [以太坊源码](https://github.com/ethereum)

* [小蚁源码](https://github.com/neo-project/)

* [EOS项目源码](https://github.com/EOSIO/eos)


</br>

******

</br>

### <a name="sdk">SDK工具包</a>

* [Truffle](https://github.com/trufflesuite/truffle) 以太坊Dapp开发脚手架

* [Cakeshop](https://github.com/jpmorganchase/cakeshop) 来自JP Morgan的以太坊可视化管理工具

* [Zeppelin](https://github.com/OpenZeppelin/zeppelin-solidity) 用于编写安全的以太坊合约框架

* [Web3j](https://github.com/web3j/web3j) 以太坊官方轻量级java SDK

* [Porosity](https://github.com/comaeio/porosity) 反编译以太坊只能合约工具

* [Composer](https://github.com/hyperledger/composer) 官方可视化Fabric应用开发框架 


</br>

******

</br>

### <a name="material">技术文档</a>

* [区块链技术博客](http://me.tryblockchain.org/) 关注以太坊

* [Solidity语言文档](http://www.tryblockchain.org/) Solidity中文手册

* [Web3Js接口文档](http://web3.tryblockchain.org/) Web3Js中文手册

* [Truffle框架文档](http://truffle.tryblockchain.org/) Truffle中文手册

* [以太坊常见问题](http://8btc.com/thread-23195-1-1.html) 以太坊常见问题FAQ


</br>

******

</br>

### <a name="datum">资料文档</a>

* [国内区块链发展现状](https://mp.weixin.qq.com/s/czhOKCH-U5tZKLdclnlx_g)

</br>

******

</br>

### <a name="blockchainbrower">区块链浏览器</a>

* [Blockchain](https://blockchain.info/) 比特币区块链浏览器

* [Etherscan](https://etherscan.io/) 以太坊区块链浏览器

* [ripplecharts](http://www.ripplecharts.com/#/graph/) 瑞波币浏览器 


</br>

******

</br>

### <a name="wallet">Wallet钱包</a>

* [My Ether Wallet](https://myetherwallet.com/)

* [MetaMask](https://metamask.io/)

* [Multi-platform Jaxx Wallet](https://jaxx.io/)

* [Mist Wallet](https://github.com/ethereum/mist/releases) 

* [Parity Wallet](https://github.com/paritytech/parity/releases/tag/v1.9.4)

* [Harmony Wallet](https://github.com/ether-camp/ethereum-harmony/releases/tag/v2.1b61)

* [imToken](https://token.im/)

* [Ledger Nano S](https://theethereum.wiki/w/index.php/Ledger_Nano_S) 

* [Trezor](https://blog.trezor.io/trezor-integration-with-myetherwallet-3e217a652e08?gi=d000c64abd1b)


</br>

******

</br>

### <a name="currency">虚拟币种</a>

* [比特币 BTC](https://www.feixiaohao.com/)

* [以太坊 ETH](https://www.feixiaohao.com/currencies/ethereum/)

* [瑞波币 XRP](https://www.feixiaohao.com/currencies/ripple/)  

* [比特现金 BCC](https://www.feixiaohao.com/currencies/bitcoin-cash/)

* [莱特币 LTC](https://www.feixiaohao.com/currencies/litecoin/) 

* [艾达币 ADA](https://www.feixiaohao.com/currencies/cardano/)

* [小蚁币 NEO](https://www.feixiaohao.com/currencies/neo/)

* [恒星币 XLM](https://www.feixiaohao.com/currencies/stellar/)

* [门罗币 XMR](https://www.feixiaohao.com/currencies/monero/)

* [柚子 EOS](https://www.feixiaohao.com/currencies/eos/)

* [埃欧塔 IOTA](https://www.feixiaohao.com/currencies/iota/)

* [达世币 DASH](https://www.feixiaohao.com/currencies/dash/)

* [新经币 NEM](https://www.feixiaohao.com/currencies/nem/)

* [波场 TRON](https://www.feixiaohao.com/currencies/tron/)

* [以太经典 ETC](https://www.feixiaohao.com/currencies/ethereum-classic/)

* [泰达币 USDT](https://www.feixiaohao.com/currencies/tether/)

* [唯链 VEN](https://www.feixiaohao.com/currencies/vechain/)

* [量子链 QTUM](https://www.feixiaohao.com/currencies/qtum/) 

* [应用链 LSK](https://www.feixiaohao.com/currencies/lisk/) 

* [比特黄金 BTG](https://www.feixiaohao.com/currencies/bitcoin-gold/) 

* [更多币种......](https://www.feixiaohao.com/)


</br>

******

</br>

### <a name="website">交易网站</a>

* [ok国际](https://www.okcoin.com/)

* [火币pro](https://www.huobi.pro/zh-cn/)

* [币安](https://www.binance.com/)


</br>

******

</br>

### <a name="webapi">交易API</a> 
