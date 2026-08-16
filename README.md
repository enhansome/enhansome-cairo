# Awesome Cairo with stars

A curated list of Cairo 1.0 code and resources.

"A Cairo Wikipedia" \~StarknetAfrica

## Contents

* [Awesome Cairo     ](#awesome-cairo-----)
  * [Contents](#contents)
  * [Libraries](#libraries)
  * [Cairo VM](#cairo-vm)
  * [Misc](#misc)
  * [Projects](#projects)
  * [References](#references)
  * [Templates](#templates)
  * [Tools](#tools)
  * [Tutorials](#tutorials)
  * [Other Lists](#other-lists)
    * [Starknet](#starknet)
    * [Cairo 0.x](#cairo-0x)
  * [License](#license)

Other Starknet/Cairo related lists: [Other lists](#other-lists)

## Libraries

* [`corelib`](https://github.com/starkware-libs/cairo/tree/main/corelib/src) ⭐ 1,900 | 🐛 212 | 🌐 Rust | 📅 2026-08-16 - Built in Cairo 1.0 standard library
* [`cairo-contracts`](https://github.com/OpenZeppelin/cairo-contracts/tree/cairo-1) ⭐ 911 | 🐛 53 | 🌐 Rust | 📅 2026-08-12 – OpenZeppelin's cairo1 development branch
* [`alexandria`](https://github.com/keep-starknet-strange/alexandria) ⭐ 265 | 🐛 0 | 🌐 Cairo | 📅 2026-03-05 – Community maintained standard library for Cairo 1.0
* [`orion`](https://github.com/gizatechxyz/orion) ⚠️ Archived - library for verifiable ML inference in Cairo 1.0
* [`cubit`](https://github.com/influenceth/cubit) ⭐ 41 | 🐛 6 | 🌐 Rust | 📅 2026-07-16 – A fixed point math library in 64.64 representation built for Cairo 1.0
* [`cairo_ml`](https://github.com/raphaelDkhn/cairo_ml) ⚠️ Archived – Build neural network models in Cairo 1.0 to perform inference
* [`suna`](https://github.com/auditless/suna) ⭐ 19 | 🐛 4 | 🌐 Rust | 📅 2023-06-12 – Typesafe primitives for Cairo 1.0 with a focus on DeFi protocols
* [`erc721.cairo`](https://github.com/reddio-com/cairo/blob/main/token/ERC721/erc721.cairo) ⭐ 18 | 🐛 0 | 🌐 Cairo | 📅 2023-12-01 – An early ERC721 implementation
* [`arcade-accounts`](https://github.com/BibliothecaDAO/arcade-account) ⭐ 17 | 🐛 1 | 🌐 Cairo | 📅 2024-02-17 - Starknet Accounts with fine grain permissions for use in onchain games
* [`neural-network-cairo`](https://github.com/franalgaba/neural-network-cairo) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2023-04-01 – Neural Network for MNIST in Cairo 1.0
* [`graffiti`](https://github.com/milancermak/graffiti/) ⭐ 8 | 🐛 0 | 🌐 Cairo | 📅 2024-01-27 - A Cairo library for building XML based documents
* [`fp`](https://github.com/baitcode/cairo-fixed-point-arithmetic) ⭐ 7 | 🐛 0 | 🌐 Cairo | 📅 2025-02-12 – Another Cairo 1 fixed point math library in 123.128 representation with storage packing implementation.

**[back to top](#contents)**

## Cairo VM

* [`cairo-zig`](https://github.com/keep-starknet-strange/cairo-zig) ⭐ 88 | 🐛 18 | 🌐 Zig | 📅 2024-08-20 - Cairo VM in Zig.
* [`cairo-vm-go`](https://github.com/NethermindEth/cairo-vm-go) ⭐ 87 | 🐛 13 | 🌐 Go | 📅 2025-06-20 - A virtual machine for Cairo written in Go.
* [`cairo-vm-ts`](https://github.com/kkrt-labs/cairo-vm-ts) ⭐ 20 | 🐛 15 | 🌐 TypeScript | 📅 2024-10-07 - A typescript implementation of the Cairo VM.
* [`cairo-vm`](https://github.com/lambdaclass/cairo-vm) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-04-09 - cairo-vm is a Rust implementation of the Cairo VM.

**[back to top](#contents)**

## Misc

* [Cairo 1.0 dashboard](https://starkscan.co/cairo-one) – Starkscan Cairo 1.0 dashboard

## Projects

* [`dojo`](https://github.com/dojoengine/dojo) ⭐ 477 | 🐛 19 | 🌐 Rust | 📅 2026-05-06 – A full stack toolchain for developing onchain games in Cairo
* [`kakarot-ssj`](https://github.com/sayajin-labs/kakarot-ssj) ⚠️ Archived – Kakarot ZK-EVM in Cairo 1.0
* [`Realms: Eternum`](https://github.com/BibliothecaDAO/eternum) ⭐ 91 | 🐛 14 | 🌐 TypeScript | 📅 2026-08-16 – Realms Autonomous World built with [`dojo`](https://github.com/dojoengine/dojo) ⭐ 477 | 🐛 19 | 🌐 Rust | 📅 2026-05-06
* [`Loot Survivor`](https://github.com/BibliothecaDAO/loot-survivor) ⭐ 89 | 🐛 3 | 🌐 Cairo | 📅 2024-08-07 - Roguelike single felt onchain game
* [`InstaSwap`](https://github.com/BibliothecaDAO/InstaSwap) ⭐ 20 | 🐛 0 | 🌐 TypeScript | 📅 2024-01-09 – Decentralized token swap protocol for ERC-1155 tokens on Starknet.
* [`starknet-commit-reveal`](https://github.com/gaetbout/starknet-commit-reveal) ⭐ 18 | 🐛 0 | 🌐 Cairo | 📅 2023-11-01 – Commit-reveal implementation
* [`kass`](https://github.com/ruleslabs/kass) ⭐ 16 | 🐛 0 | 🌐 Solidity | 📅 2023-08-13 – L1 <-> L2 Starknet ERC1155 Bridge
* [`Cairo1.0 by Examples`](https://github.com/CeliktepeMurat/Cairo1.0_by_Examples/tree/main) ⭐ 14 | 🐛 1 | 🌐 Cairo | 📅 2023-02-22 – Cairo 1.0 examples
* [`RockPaperScissors-Cairo`](https://github.com/Kalzak/RockPaperScissors-Cairo/tree/main) ⭐ 3 | 🐛 0 | 🌐 Cairo | 📅 2023-04-05 – Commit-reveal based Rock-Paper-Scissors
* [`2wrds_cntrcts`](https://github.com/greged93/2wrds_cntrcts) ⭐ 1 | 🐛 0 | 🌐 Cairo | 📅 2023-05-20 – 2wrds project
* [`rollyourown`](https://github.com/cartridge-gg/rollyourown) – On-chain adaptation of the original Drug Wars game
* [`shoshin-cairo1`](https://github.com/topology-gg/shoshin-cairo-1) – On-chain fighting game in Cairo 1
* [`bto-cairo-1`](https://github.com/topology-gg/bto-cairo-1) – Binary Tree Operations in Cairo 1

**[back to top](#contents)**

## References

* [`starkware-libs/cairo/docs`](https://github.com/starkware-libs/cairo/tree/main/docs/reference) ⭐ 1,900 | 🐛 212 | 🌐 Rust | 📅 2026-08-16 – Official Cairo 1.0 reference

**[back to top](#contents)**

## Templates

* [`starknet-erc721`](https://github.com/starknet-edu/starknet-erc721) ⚠️ Archived - Learn how to deploy and customize an ERC721 token on StarkNet
* [`auditless/cairo-template`](https://github.com/auditless/cairo-template) ⭐ 87 | 🐛 0 | 🌐 Rust | 📅 2023-06-01 – A minimal template for building smart contracts with Cairo 1.0
* [`starknet-erc20`](https://github.com/starknet-edu/starknet-erc20) ⚠️ Archived - Learn how to deploy and customize an ERC20 token on StarkNet
* [`msaug/cairo1-template`](https://github.com/msaug/cairo1-template) ⭐ 43 | 🐛 0 | 🌐 Cairo | 📅 2023-04-04 – A template to get you started with Cairo 1
* [`ArgentX Cairo template`](https://github.com/argentlabs/starknet-build/tree/main/cairo1.0) ⚠️ Archived – ArgentX Cairo template
* [`cairo1-mocha`](https://github.com/enitrat/cairo1-mocha) ⭐ 2 | 🐛 0 | 🌐 Cairo | 📅 2023-05-02 – This project aims to provide a simple way of testing your contracts using Mocha and StarknetJS

**[back to top](#contents)**

## Tools

* [`scarb`](https://docs.swmansion.com/scarb) – The project management tool for the Cairo language
* [`protostar`](https://docs.swmansion.com/protostar) – The Starknet smart contract development toolchain
* [`WASM-Cairo`](https://github.com/cryptonerdcn/wasm-cairo) ⭐ 60 | 🐛 9 | 🌐 Rust | 📅 2026-03-16 – A suite of development tools based on WebAssembly for the Cairo language and the Starknet smart contract

**[back to top](#contents)**

## Tutorials

* [`starklings-cairo1`](https://github.com/shramee/starklings-cairo1) ⭐ 473 | 🐛 7 | 🌐 Cairo | 📅 2026-08-08 – An interactive tutorial to get you up and running with Cairo and Starknet
* [The Cairo Book](https://github.com/cairo-book/cairo-book.github.io) ⭐ 276 | 🐛 13 | 🌐 Cairo | 📅 2026-08-03 – The Cairo Programming Language Book
* [`deploy-cairo1-demo`](https://github.com/starknet-edu/deploy-cairo1-demo) ⚠️ Archived – Official StarkWare tutorial for deploying a Cairo 1 contract
* [`Cairo1.0`](https://github.com/Starknet-Africa-Edu/Cairo1.0) ⚠️ Archived – Mini Cairo 1.0 tutorial by Starknet Africa
* [`0to1CairoDemo`](https://github.com/NethermindEth/0to1CairoDemo) ⭐ 8 | 🐛 3 | 🌐 Python | 📅 2025-08-05 – Steps to upgrade from cairo 0 upgradeable contract to cairo 1 upgradeable contract
* [`HERDAO-cairo`](https://github.com/omarespejel/HERDAO-Cairo) ⭐ 5 | 🐛 0 | 🌐 Rust | 📅 2023-03-10 - First smart contracts with Cairo and HER DAO
* [`starknet-accounts-cairo1`](https://github.com/FelixGibson/starknet-accounts-cairo1) ⭐ 4 | 🐛 0 | 🌐 Cairo | 📅 2023-03-21 – Starknet account abstraction workshop
* [`starklings-cairo1` solutions](https://github.com/Akashneelesh/starklings-cairo1) ⭐ 0 | 🐛 0 | 📅 2023-03-27 – Solutions to starklings exercises
* [Getting Started with Cairo 1.0](https://www.argent.xyz/blog/getting-started-with-cairo-1.0/) – Learn everything you need to know about the new and improved Cairo
* [A First Look at Cairo 1.0](https://medium.com/nethermind-eth/a-first-look-at-cairo-1-0-a-safer-stronger-simpler-provable-programming-language-892ce4c07b38) – This blog post will take you through the new features added to Cairo and discuss how they will improve the language
* [Reading Sierra: Starknet's secret sauce for Cairo 1.0](https://medium.com/yagi-fi/reading-sierra-starknets-secret-sauce-for-cairo-1-0-5bc73409e43c) – A tutorial for reading Sierra
* [How to write ERC721 contracts with Cairo 1.0](https://blog.reddio.com/how-to-write-erc721-contracts-with-cairo-1/) – Guide to writing an ERC721 contract
* [Under the hood of Cairo 1.0: Exploring Sierra](https://medium.com/nethermind-eth/under-the-hood-of-cairo-1-0-exploring-sierra-7f32808421f5) – A deep-dive into the purpose of Sierra
* [`cairopractice`](https://cairopractice.com/) - Cairo 1.0 and Starknet blog

**[back to top](#contents)**

## Other Lists

### Starknet

* [`awesome-starknet`](https://github.com/gakonst/awesome-starknet) ⭐ 1,551 | 🐛 20 | 📅 2025-01-06 A curated list of awesome Starknet resources, libraries, tools and more

### Cairo 0.x

* [`cairo-goldmine`](https://github.com/beautyisourbusiness/cairo-goldmine) ⭐ 292 | 🐛 2 | 📅 2022-10-12 A comprehensive, annotated list of repositories of the Starknet ecosystem
* [`cairo-resources-list`](https://github.com/NewtonDAO/cairo-resources-list) ⭐ 66 | 🐛 1 | 📅 2022-11-14 A curated list of awesome Cairo resources, libraries, tools and more
* [`newton`](https://www.newton.so) A series of Q\&As and FAQs about StarkNet developer tools and Cairo 0.x

**[back to top](#contents)**

## License

[MIT](https://github.com/auditless/cairo-template/blob/main/LICENSE) ⭐ 87 | 🐛 0 | 🌐 Rust | 📅 2023-06-01 © [Auditless Limited](https://www.auditless.com)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
