# EVM-Book
A collection of EVM related information. This is a repo that I created for myself to keep track of all the useful links/information I have come across related to the EVM and put it in one place. I made it public in case anyone else wants to use it to explore specific EVM related topics. This document is a work in progess and will continually be updated.



<br>

## Low Level EVM Info
[Every EVM Opcode and cost](https://www.evm.codes/)

[Solidity -> Bytecode -> Opcodes](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy?s=r)

[Memory Deep Dive](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy-d6b?s=r)

[The EVM chapter in the Ethereum Book](https://github.com/ethereumbook/ethereumbook/blob/develop/13evm.asciidoc)

[EVM Puzzles: Use calldata, calvalues and opcodes to solve EVM challenges](https://github.com/fvictorio/evm-puzzles)

[Diving into EVM](https://medium.com/@hayeah)



<br>


## Tooling / Testing

[Foundry](https://onbjerg.github.io/foundry-book/)

[Hardhat](https://hardhat.org/) (for when the task is outside of the bounds of Foundry)

[Tenderly: Block explorer that provides very detailed transaction info.](https://dashboard.tenderly.co/explorer?utm_source=homepage)

[DethCode: While browsing smart contract code on Etherscan, change URL from `.io` to `.deth.net`. This will open Visual Studio Code instance and fetch the verified code using Etherscan API.](https://twitter.com/dethcrypto/status/1471173109998882819)


<br>


## Security 

[Smart contract security - key principles](https://consensys.github.io/smart-contract-best-practices/general-philosophy/)

[Comprehensive list of known attack vectors and common anti-patterns](https://blog.sigmaprime.io/solidity-security.html)

[Smart Contract Programmer's Hack Solidity Playlist](https://www.youtube.com/watch?v=4Mm3BCyHtDY&list=PLO5VPQH6OWdWsCgXJT9UuzgbC8SPvTRi5)

[Smartbugs: A curated dataset of vulnerable solidity smart contracts](https://github.com/smartbugs/smartbugs/tree/master/dataset)

Use [Slither](https://github.com/crytic/slither) AND [Mythril](https://github.com/ConsenSys/mythril) together for automated vunerability testing. This does not replace an audit. This is like scanning a contract at a high level and only picks up [~37% of vunerabilities accurately](https://soliditydeveloper.com/smart-contract-security-analyzers)

[List of all up to date Solidity compiler bugs](https://github.com/ethereum/solidity/blob/develop/docs/bugs.json)

[Damn Vulnerabile Defi: Smart contract offensive security challenges](https://www.damnvulnerabledefi.xyz/) (Or try the [Foundry Version)](https://github.com/nicolasgarcia214/damn-vulnerable-defi-foundry)

[Solcurity: A security and code quality checklist](https://github.com/Rari-Capital/solcurity)


<br>


## Gas Optimizations

[Solmate: gas optimized building blocks for smart contract development.](https://github.com/Rari-Capital/solmate/)

[How arithmetic with values less than 32bytes are handled and why it costs more gas](https://ethereum.stackexchange.com/questions/3067/why-does-uint8-cost-more-gas-than-uint256)

[Patterns / Optimizations for gas savings](https://github.com/kadenzipfel/gas-optimizations)

<br>


## Yul
[Yul Docs](https://docs.soliditylang.org/en/latest/yul.html) 

[Yul+ Docs](https://github.com/FuelLabs/yulp)

[Yul+ Walkthrough](https://fuellabs.medium.com/introducing-yul-a-new-low-level-language-for-ethereum-aa64ce89512f)

[Inlining Yul In Solidity](https://docs.soliditylang.org/en/v0.8.12/assembly.html#inline-assembly)

[Accessing Memory Explanation](https://ethereum.stackexchange.com/questions/34529/understanding-solidity-inline-assembly-code)

[Vunerable Yul Patterns](https://github.com/Mikerah/solidity-bugs-and-vulns-in-yul)


<br>

## Zero Knowledge


<br>

## General/Misc


[Conventions in Solidity](https://docs.soliditylang.org/en/v0.8.12/assembly.html#conventions-in-solidity)

[ControlCPlusControlV's Yul (and Some Solidity) Optimizations and Tricks](https://hackmd.io/50TB8ZOTSCSWsfz0l0aF2g)


<br>


