# Repositories

An overview of the main projects we are maintaining under "Public Goods"

## Core Rust Libraries

* [CosmWasm/cosmwasm](https://github.com/CosmWasm/cosmwasm) - Monorepo with cosmwasm-vm, core contract sdk, and tools
* [CosmWasm/wasmvm](https://github.com/CosmWasm/wasmvm) - FFI bindings to Go for integration with Cosmos SDK
* [CosmWasm/serde-json-wasm](https://github.com/CosmWasm/serde-json-wasm) - Customized JSON lib to work with our restricted no-float, Wasm environment

## Cosmos SDK Libraries 

* [CosmWasm/wasmd](https://github.com/CosmWasm/wasmd) - Provides `x/wasm` module for easy embedding into any Cosmos SDK blockchains. Also includes sample application and integration examples.
* [CosmWasm/token-factory](https://github.com/CosmWasm/token-factory) - (In-Progress) refactoring of Osmosis' Token Factory to be a general CosmWasm extension
* [CosmWasm/token-binding](https://github.com/CosmWasm/token-bindings) - (In-Progress) Rust contract bindings to the above

## Core Contract SDK

* [CosmWasm/cw-plus](https://github.com/CosmWasm/cw-plus) - Many sample contracts to use or learn from. Like OpenZeppelin for Ethereum
* [CosmWasm/cw-storage-plus](https://github.com/CosmWasm/cw-storage-plus) - Powerful layer for state management and queries. Used by almost all modern contracts.
* [CosmWasm/cw-utils](https://github.com/CosmWasm/cw-util) - General utilities around payments, replies, etc used by many contracts. 
* [CosmWasm/cw-multi-test](https://github.com/CosmWasm/cw-multi-test) - Powerful framework to test cross-contract calls in native rust in simulated blockchain environment
* [CosmWasm/cw-template](https://github.com/CosmWasm/cw-template) - Starter pack to bootstrap your contract with some best practices
* [CosmWasm/rust-optimizer](https://github.com/CosmWasm/rust-optimizer) - Reproducible build system for size-optimized contracts, used on most production deployments 
* [CosmWasm/serde-cw-value](https://github.com/CosmWasm/serde-cw-value) - Parse arbitrary JSON data and inspect it
* [CosmWasm/sylvia](https://github.com/CosmWasm/sylvia) - Leveraging macros to make a simpler API on top of the standard CosmWasm SDK

## CosmJS Related

* [cosmos/cosmjs](https://github.com/cosmos/cosmjs) - The core client side JS/TS library for writing dApps in the Cosmos - for both CosmWasm and native SDK modules
* [confio/cosmjs-types](https://github.com/confio/cosmjs-types) - Generated types for SDK modules based on protobuf definitions. Much thanks to Cosmology hereA

## IBC Related

* confio/ts-relayer
* confio/cw-ibc-demo
* confio/ibc-tests-cw20
* confio/relayer-ci-images 

## Documentation

* CosmWasm/book
* CosmWasm/resources
* CosmWasm/cw-awesome
* CosmWasm/advisories


## Other Tools

* CosmWasm/cosmwasm-go
* CosmWasm/tinygo
* confio/decode-raw
* CosmWasm/code-explorer
