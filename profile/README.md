# Coin Shuffle

This organization provides implementations of **Coin Shuffle** process.

## Repos


+ [`service`](https://github.com/coin-shuffle/service) - implementation of centralized service that
  connects participants of **Coin Shuffle** process.
+ [`node`](https://github.com/coin-shuffle/node) - command line implementation of participant (_node_)
  in **Coin Shuffle** process.
+ [`core`](https://github.com/coin-shuffle/core) - Rust library that contains all **Coin Shuffle**
  process logic separate from protocol implementation.
+ [`contracts-bindigs`](https://github.com/coin-shuffle/contracts-bindings) - Rust library that contains
  Rust defenitions for `core-contracts`
+ [`core-contracts`](https://github.com/coin-shuffle/core-contracts) - core contracts for Ethereum written
  in Solidity using Hardhat.
+ [`protobuf`](https://github.com/coin-shuffle/protobuf) - all protobuf definitions used in protocol level
  implementation
+ [`protos`](https://github.com/coin-shuffle/protos) - Rust library that contains Rust defenitions
  generated from `protobuf`
