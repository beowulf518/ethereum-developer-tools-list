
# Ethereum Developer Tools List
A guide to available tools, components, patterns, and platforms for developing applications on Ethereum.

Creation of this list was spurred by product managers at ConsenSys who saw a need for better sharing of tools, development patterns, and components amongst both new and experienced blockchain developers.

This resource is meant to be focused on developer tools, but the repo also includes:
* [Ethereum Ecosystem Resources](EcosystemResources.md) for useful DApps, educational resources, wallets, and services.

## Contributions are welcome!

Feel free to submit a pull request, with anything from small fixes to tools you'd like to add. If adding a new tool, **please add a brief description** that you think new developers would understand.

Many thanks to the 20+ contributors including [@corbpage](https://twitter.com/corbpage) of Meridio for the idea, [@pakaplace](https://twitter.com/Parker_Place) for expanding and curating, and @jpantunes for restructuring the list in a more logical way.
* Projects that do not have a working product will not be added.
* Projects that are deprecated or no longer maintained will be removed.
* Projects that are paid/restricted services without open source code or developer reviews will be further vetted.

^Is the above fair? Share your input here - https://github.com/ConsenSysLabs/ethereum-developer-tools-list/pull/70

## New developers start here
* [Solidity](http://solidity.readthedocs.io/en/latest/) - The most popular smart contract language. 
* [Truffle](http://truffleframework.com) - Most popular smart contract development, testing, and deployment framework. Install the cli via npm and start here to write your first smart contracts.
* [Metamask](https://metamask.io/) - Chrome extension wallet to interact with Dapps.
* [Truffle boxes](http://truffleframework.com/boxes/) - Packaged components for the Ethereum ecosystem

## Developer Tools
### Developing Smart Contracts
#### Smart Contract Languages
* [Solidity](http://solidity.readthedocs.io/en/latest/)- Ethereum smart contracting language
* [Bamboo](https://github.com/pirapira/bamboo) - A morphing smart contract language
* [Vyper](https://github.com/ethereum/vyper) - New experimental programming language
* [LLL](https://media.consensys.net/an-introduction-to-lll-for-ethereum-smart-contract-development-e26e38ea6c23) - Low-level Lisp-like Language

#### Frameworks
* [Truffle](http://truffleframework.com) - Most popular smart contract development, testing, and deployment framework. The Truffle suite includes Truffle, [Ganache](https://github.com/trufflesuite/ganache), and Drizzle. [Deep dive on Truffle here](https://media.consensys.net/truffle-deep-dive-what-you-need-to-know-when-developing-on-ethereum-e548d4df6e9)
* [Embark](https://github.com/embark-framework/embark) - Framework for DApp development
* [Dapp](https://github.com/dapphub/dapptools/tree/master/src/dapp) - Framework for DApp development, successor to DApple
* [Populus](https://github.com/ethereum/populus) - The Ethereum development framework with the most cute animal pictures
* [Etherlime](https://github.com/LimeChain/etherlime) - ethers.js based framework for Dapp deployment
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Simplifies integration and accepting testing of smart contract applications with docker instances that closely resembles a real blockchain network

#### IDEs
* [Remix](https://remix.ethereum.org/) - Web IDE with built in static analysis, test blockchain VM.
* [Atom](https://atom.io/) - Atom editor with [Atom Solidity Linter](https://atom.io/packages/atom-solidity-linter), [Etheratom](https://atom.io/packages/etheratom)
* [Pragma](https://www.withpragma.com/) - Very simple web IDE for solidity, and auto-generated interfaces for smart contracts.
[autocomplete-solidity](https://atom.io/packages/autocomplete-solidity), and [language-solidity](https://atom.io/packages/language-solidity) packages

* [Superblocks Studio](https://superblocks.com/studio/) - Superblocks Studio helps you code, build, and deploy your smart contracts.
* [Vim solidity](https://github.com/tomlion/vim-solidity) - Vim syntax file for solidity
* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - Visual Studio Code extension that adds support for Solidity
* [Intellij Solidity Plugin](https://github.com/intellij-solidity/intellij-solidity/wiki) - Open-source plug-in for [JetBrains IntelliJ Idea IDE](https://www.jetbrains.com/idea/) (free/commercial) with syntax highlighting, formatting, code completion etc. 
* [YAKINDU Solidity Tools](https://github.com/Yakindu/solidity-ide) - Eclipse based IDE. Features context sensitive code completion and help, code navigation, syntax coloring, build in compiler, quick fixes and templates. 

### Test blockchain networks
* [Ganache](https://github.com/trufflesuite/ganache) - App for test Ethereum blockchain with visual UI and logs
* [Kaleido](https://kaleido.io/) - Use Kaleido for spinning up a consortium blockchain network. Great for PoCs and testing
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Run a local Raiden network in docker containers for demo and testing purposes
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - Out-of-the-box deployment scripts for private PoA networks
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Out-of-the-box deployment scripts for private PoW networks

#### Test Ether faucets
* [Rinkeby faucet](https://faucet.rinkeby.io/)
* [Kovan faucet](https://github.com/kovan-testnet/faucet)
* [Ropsten faucet](http://faucet.ropsten.be:3001/)

### Communicating with Ethereum
#### Frontend Ethereum APIs
* [Web3.js](https://github.com/ethereum/web3.js/) - Javascript Web3
    * [Eth.js](https://github.com/ethjs) - Javascript Web3 alternative
    * [Ethers.js](https://github.com/ethers-io/ethers.js/)- Javascript Web3 alternative, useful utilities and wallet features
    * [Web3Wrapper](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/web3-wrapper)- Typescript Web3 alternative
    * [Ethereumjs](https://github.com/ethereumjs/) - A collection of utility functions for Ethereum like [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) and [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx)

* [Drizzle](https://github.com/truffle-box/drizzle-box) -  Redux library to connect a frontend to a blockchain
* [Subproviders](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/subproviders) - Several useful subproviders to use in conjunction with [Web3-provider-engine](https://github.com/MetaMask/provider-engine/) (including a LedgerSubprovider for adding Ledger hardware wallet support to your dApp)
* [web3-webpacked](https://github.com/NoahHydro/web3-webpacked) - JS framework to manage web3 injection
* [Vortex](https://github.com/Horyus/vortex) - A Dapp-ready Redux Store. Smart and Dynamic background data refresh thanks to WebSockets. Works with [Truffle](https://github.com/Horyus/vortex-demo) and [Embark](https://github.com/Horyus/vortex-demo-embark).

#### Backend Ethereum APIs
* [Web3.py](https://github.com/ethereum/web3.py)- Python Web3
* [Web3.php](https://github.com/sc0Vu/web3.php) - PHP Web3
* [Web3j](https://github.com/web3j/web3j) - Java Web3
* [Nethereum](https://nethereum.com/) - .Net Web3
* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - Ruby Web3
* [Web3.hs](http://hackage.haskell.org/package/web3) - Haskell Web3
* [KEthereum](https://github.com/walleth/kethereum) - Kotlin Web3
* [Pyethereum](https://github.com/ethereum/pyethereum) - The Python core library of the Ethereum project
* [Eventeum](https://github.com/ConsenSys/eventeum) - A bridge between Ethereum smart contract events and backend microservices, written in Java by Kauri

#### Bootstrap/out of box tools
* [Truffle boxes](http://truffleframework.com/boxes/) - Packaged components for the Ethereum ecosystem
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Run a local Raiden network in docker containers for demo and testing purposes
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - Out-of-the-box deployment scripts for private PoA networks
* [Parity Demo-PoA Tutorial](https://wiki.parity.io/Demo-PoA-tutorial.html) - Step-by-Step tutorial for building a PoA test chain with 2 nodes with Parity authority round consensus
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Out-of-the-box deployment scripts for private PoW networks
* [Kaleido](https://kaleido.io/) - Use Kaleido for spinning up a consortium blockchain network. Great for PoCs and testing
* [Cheshire](https://github.com/endless-nameless-inc/cheshire) - A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box

#### Ethereum ABI (Application Binary Interface) tools
* [ABI decoder](https://github.com/ConsenSys/abi-decoder) - library for decoding data params and events from Ethereum transactions
* [ABI-gen](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/abi-gen) - Generate Typescript contract wrappers from contract ABI's.
* [Ethereum ABI UI](https://github.com/hiddentao/ethereum-abi-ui) - Auto-generate UI form field definitions and associated validators from an Ethereum contract ABI

#### Patterns & Best Practices

##### Patterns for Smart Contract Development
* [Dappsys: Safe, simple, and flexible Ethereum contract building blocks](https://github.com/dapphub/dappsys)
    * has solutions for common problems in Ethereum/Solidity, eg.
        * [Whitelisting](https://steemit.com/ethereum/@nexusdev/dapp-a-day-11-whitelist-boring)
        * [Upgradable ERC20-Token](https://steemit.com/ethereum/@nikolai/dapp-a-day-6-upgradeable-tokens)
        * [ERC20-Token-Vault](https://steemit.com/ethereum/@nexusdev/dapp-a-day-18-erc20-token-vault)
        * [Authentication (RBAC)](https://steemit.com/ethereum/@nikolai/dapp-a-day-4-access-control-via-auth)
        * [...several more...](https://github.com/dapphub/dappsys)
    * provides building blocks for the [MakerDAO](https://github.com/makerdao/maker-otc) or [The TAO](https://ryepdx.github.io/the-tao/)
    * should be consulted before creating own, untested, solutions
    * usage is described in [Dapp-a-day 1-10](https://steemit.com/@nikolai) and [Dapp-a-day 11-25](https://steemit.com/@nexusdev)
* [OpenZeppelin: An open framework of reusable and secure smart contracts in the Solidity language.](http://zeppelin-solidity.readthedocs.io/en/latest/) 
    * Likely the most widely-used libraries and smart contracts
    * Similar to Dappsys, more integrated into Truffle framework
    * [Blog about Best Practices with Security Audits](https://medium.com/zeppelin-blog)
* [Advanced Workshop with Assembly](https://github.com/androlo/solidity-workshop)
* [Simpler Ethereum Multisig](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037) - especially section _Benefits_

##### Upgradebility
* [Blog von Elena Dimitrova, Dev at colony.io](https://blog.colony.io/@elena_di)
    * https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948
    * https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88
* [Techblog von Aragon](https://blog.aragon.one/tagged/development)
    * [Library driven development](https://blog.aragon.one/library-driven-development-in-solidity-2bebcaf88736)
* [OpenZeppelin on Proxy Libraries](https://medium.com/zeppelin-blog/proxy-libraries-in-solidity-79fbe4b970fd)

### Infrastructure
#### Ethereum Clients
* [Geth](https://github.com/ethereum/go-ethereum/wiki/geth) - Go client
* [Parity](https://www.parity.io/) - Rust client
* [Cpp-ethereum](https://github.com/ethereum/cpp-ethereum) - C++ client
* [Pyethapp](https://github.com/ethereum/pyethapp) - Python client using [pyethereum](https://github.com/ethereum/pyethereum)
* [Trinity](https://github.com/ethereum/trinity) - Python client using [py-evm](https://github.com/ethereum/py-evm)
* [Ethereumjs](https://github.com/ethereumjs/ethereumjs-client) - JS client using [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm)
* [Ethereumj](https://github.com/ethereum/ethereumj) - Java client by the Ethereum Foundation
* [Harmony](https://github.com/ether-camp/ethereum-harmony) - Java client by EtherCamp
* [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth) - Seth is an Ethereum client tool—like a "MetaMask for the command line"
* [Mustekala](https://github.com/MetaMask/mustekala) - Ethereum Light Client project of Metamask.
* [Exthereum](https://github.com/exthereum/blockchain) - Elixir client
* [EWF Parity](https://github.com/energywebfoundation/energyweb-client) - Energy Web Foundation client for the Tobalaba test network
* [Quorum](https://github.com/jpmorganchase/quorum) - A permissioned implementation of Ethereum supporting data privacy by [JP Morgan](https://www.jpmorgan.com/quorum)

#### Storage
* [IPFS](https://ipfs.io/) - Decentralised storage and file referencing
   * [IPFS-Store](https://github.com/ConsenSys/IPFS-Store) - IPFS Storage service with added search capability
   * [OrbitDB](https://github.com/orbitdb/orbit-db) - Decentralised database on top of IPFS
   * [JS IPFS API](https://github.com/ipfs/js-ipfs-api) - A client library for the IPFS HTTP API, implemented in JavaScript.
* [Swarm](http://swarm-gateways.net/) - Distributed storage platform and content distribution service, a native base layer service of the Ethereum web3 stack

#### Messaging
* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - Communication protocol for DApps to communicate with each other, a native base layer service of the Ethereum web3 stack
* [DEVp2p Wire Protocol](https://github.com/ethereum/wiki/wiki/%C3%90%CE%9EVp2p-Wire-Protocol) - Peer-to-peer communications between nodes running Ethereum/Whisper
* [Pydevp2p](https://github.com/ethereum/pydevp2p) - Python implementation of the RLPx network layer

### Testing Tools
* [Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-cov) - Solidity code coverage tool
* [Solidity coverage](https://github.com/sc-forks/solidity-coverage) - Alternative code coverage for Solidity smart-contracts
* [Solidity function profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler
* [Espresso](https://github.com/hillstreetlabs/espresso) - Speedy, parallelised, hot-reloading solidity test framework
* [Eth tester](https://github.com/ethereum/eth-tester) - Tool suite for testing Ethereum applications
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Simplifies integration and accepting testing of smart contract applications with docker instances that closely resembles a real blockchain network
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - The hevm project is an implementation of the Ethereum virtual machine (EVM) made specifically for unit testing and debugging smart contracts
* [Ethereum graph debugger](https://github.com/fergarrui/ethereum-graph-debugger) - Solidity graphical debugger
* [Solium](https://github.com/duaraghav8/Solium) - Linter to identify and fix style & security issues in Solidity
* [Decode](https://github.com/dteiml/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand

### Security Tools
* [Mythril](https://github.com/ConsenSys/mythril) - Static smart contract security analysis
* [Oyente](https://github.com/melonproject/oyente) - Alternative static smart contract security analysis
* [Securify](https://securify.ch) - Security scanner for Ethereum smart contracts
* [Porosity](https://github.com/comaeio/porosity) - Decompiler and Security Analysis tool for Blockchain-based Ethereum Smart-Contracts
* [Ethersplay](https://github.com/trailofbits/ethersplay) - EVM disassembler
* [Evmdis](https://github.com/Arachnid/evmdis) - Alternative EVM disassembler
* [Hydra](https://github.com/IC3Hydra/Hydra) - Framework for cryptoeconomic contract security, decentralised security bounties
* [Solgraph](https://github.com/raineorshine/solgraph) - Visualise Solidity control flow for smart contract security analysis
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool on Smart Contracts and Binaries
* [Solidity security blog](https://github.com/sigp/solidity-security-blog) - Comprehensive list of known attack vectors and common anti-patterns
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - A Collection of Vulnerabilities in ERC20 Smart Contracts With Tokens Affected

### Monitoring
* [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - A tool to monitor a number of smart contracts and transactions
* [Supermax](https://www.supermax.cool/) - A live data feed of the activities and event logs of your smart contracts on Ethereum

### Other Miscellaneous Tools
* [Truffle boxes](http://truffleframework.com/boxes/) - Packaged components for building DApps fast.
   * [Cheshire](https://github.com/endless-nameless-inc/cheshire) - A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box
* [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html?highlight=bin) - Solidity compiler
* [Sol-compiler](https://github.com/0xProject/0x-monorepo/tree/v2-prototype/packages/sol-compiler) - Project-level Solidity compiler
* [Solidity cli](https://github.com/pubkey/solidity-cli) - Compile solidity-code faster, easier and more reliable
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - Combine solidity project to flat file utility. Useful for visualizing imported contracts or for verifying your contract on Etherscan
* [RLP](https://github.com/ethereumjs/rlp) - Recursive Length Prefix Encoding in JavaScript
* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereal is a command line tool for managing common tasks in Ethereum
* [Eth crypto](https://github.com/pubkey/eth-crypto) - Cryptographic javascript-functions for Ethereum and tutorials to use them with web3js and solidity
* [Parity Signer](https://github.com/paritytech/parity-signer) - mobile app allows signing transactions
* [py-eth](http://www.py eth.com) - Collection of Python tools for the Ethereum ecosystem
* [truffle-flattener](https://github.com/alcuadrado/truffle-flattener) - Concats solidity files developed under Truffle with all of their dependencies
* [Decode](https://github.com/dteiml/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand
* [TypeChain](https://github.com/Neufund/TypeChain) - Typescript bindings for Ethereum smartcontracts

### Smart Contract Standards & Libraries
#### [ERCs](https://eips.ethereum.org/erc) - The Ethereum Request for Comment repository
* Tokens
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - Original token contract for fungible assets
  * [ERC-721](https://github.com/ethereum/eips/issues/721) - Token standard for non-fungible assets
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) -  Creates a standard method to publish and detect what interfaces a smart contract implements.
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) -  Proxy contract for key management and execution, to establish a Blockchain identity.
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - A standard interface for ownership of contracts

#### Popular Smart Contract Libraries
* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity) - Contains tested reusable smart contracts like [SafeMath](https://openzeppelin.org/api/docs/math_SafeMath.html) and ZeppelinOS [library](https://github.com/zeppelinos/zos-lib) for smart contract upgradeability
* [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) -  A group of packages built for use on blockchains utilising the Ethereum Virtual Machine
* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - A gas-efficient Solidity date and time library
* [Aragon](https://github.com/aragon/aragon) - DAO protocol
* [0x](https://github.com/0xProject) - DEX protocol


### Developer Guides for 2nd Layer Infrastructure

#### Scalability

#### Payment/State Channels
* [Ethereum Payment Channel](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc) - Ethereum Payment Channel in 50 lines of code
* [µRaiden Documentation](http://microraiden.readthedocs.io) - Guides and Samples for µRaiden Sender/Receiver Use Cases

#### Plasma
* [Plasma MVP](https://github.com/omisego/plasma-mvp) - OmiseGO's research implementation of Minimal Viable Plasma
* [Plasma MVP Golang](https://github.com/kyokan/plasma) - Golang implementation and extension of the Minimum Viable Plasma specification
* [Plasma Cash](https://github.com/mkchungs/plasma-cash) - Simple Plasma Cash implementation

#### Side-Chains
* [POA Network](https://poa.net/)
  * [POA Bridge](http://bridge.poa.net/)
  * [POA Bridge UI](https://github.com/poanetwork/bridge-ui)
  * [POA Bridge Contracts](https://github.com/poanetwork/poa-bridge-contracts)
  * [Loom Network](https://github.com/loomnetwork)
  
#### Privacy

##### zkSNARKs
* [ZoKrates](https://github.com/JacobEberhardt/ZoKrates) - A toolbox for zkSNARKS on Ethereum




