# Coin Shuffle

This organization provides demo implementation of **Coin Shuffle** process based on Ethereum blockchain with centalized coordinator (service)

See [our docs](https://coin-shuffle.github.io/docs/) for more info.

## Repos

+ [`service`](https://github.com/coin-shuffle/service) - implementation of coordinator that
  connects participants of **Coin Shuffle** process.
+ [`node-cli`](https://github.com/coin-shuffle/node-cli) - command line implementation of participant (_node_)
  in **Coin Shuffle** process.
+ [`core`](https://github.com/coin-shuffle/core) - Rust library that contains all **Coin Shuffle**
  process logic separate from network protocol implementation.
+ [`contracts-bindigs`](https://github.com/coin-shuffle/contracts-bindings) - Rust library that contains
  Rust defenitions for `core-contracts`
+ [`core-contracts`](https://github.com/coin-shuffle/core-contracts) - core contracts for Ethereum written
  in Solidity using Hardhat. (currently archived, as we are moving to Foundry)
+ [`protobuf`](https://github.com/coin-shuffle/protobuf) - all protobuf definitions used in protocol level
  implementation
+ [`protos`](https://github.com/coin-shuffle/protos) - Rust library that contains Rust defenitions
  generated from `protobuf` repo.
+ [`elysium`](https://github.com/coin-shuffle/elysium) - iOS app implementation of participant (_node_).
+ [`crypto-bridge`](https://github.com/coin-shuffle/crypto-bridge) - Rust Crypto Bridge for iOS (bindings for
  internal libs)
