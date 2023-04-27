# Coin Shuffle

This organization provides demo implementation of **Coin Shuffle** process based on Ethereum blockchain with centalized coordinator (service)

See [our docs](https://coin-shuffle.github.io/docs/) for more info.

## Repos

### Apps

+ [`node-cli`](https://github.com/coin-shuffle/node-cli) - command line implementation of participant (_node_)
  in **Coin Shuffle** process.
  
### Tools

+ [`elysium`](https://github.com/coin-shuffle/elysium) - iOS app implementation of participant (_node_).

### Services

+ [`service`](https://github.com/coin-shuffle/service) - implementation of coordinator that
  connects participants of **Coin Shuffle** process.
  
### Contracts

+ [`contracts`](https://github.com/coin-shuffle/contracts) - core contracts for Ethereum written
  in Solidity using Foundry.

### Rust libraries

+ [`core-rs`](https://github.com/coin-shuffle/core-rs) - Rust library that contains all **Coin Shuffle**
  process logic separate from network protocol implementation.
+ [`contracts-bindigs-rs`](https://github.com/coin-shuffle/contracts-bindings-rs) - Rust library that contains
  Rust defenitions for `contracts`
+ [`protos-rs`](https://github.com/coin-shuffle/protos-rs) - Rust library that contains Rust defenitions
  generated from `protobuf` repo.
+ [`crypto-bridge-rs`](https://github.com/coin-shuffle/crypto-bridge-rs) - Rust Crypto Bridge for iOS (bindings for
  internal libs)

### Protocol buffer

+ [`protobuf`](https://github.com/coin-shuffle/protobuf) - all protobuf definitions used in protocol level
  implementation
