### rust-secp256k1-sha3

`rust-secp256k1-sha3` is a wrapper around ![libsecp256k1](https://github.com/bitcoin/secp256k1),
a C library by Peter Wuille for producing ECDSA signatures using the SECG curve
`secp256k1` with ![SHA3](https://github.com/mjosaarinen/tiny_sha3) hash function. This library
* exposes type-safe Rust bindings for all `libsecp256k1` functions
* implements key generation
* implements deterministic nonce generation via RFC6979
* implements many unit tests, adding to those already present in `libsecp256k1`
* makes no allocations (except in unit tests) for efficiency and use in freestanding implementations

[Full documentation](https://docs.rs/secp256k1/0.8.3/secp256k1/)

