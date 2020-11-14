# Pypairing

This is a library for prototyping cryptographic protocols in python3. It wraps the Zcash team's Rust implementation of bls12-381 (support for more curves is unlikely). It's sort of like Charm but less ambitious and maintained by me, largely as a learning exercise.

## Documentation

Coming Soon (TM)

## Security Warnings

Like the underlaying Rust library, this library does not make any guarantees about constant-time operations, memory access patterns, or resistance to side-channel attacks. Unlike the Rust library, there's a decent chance some things here are straight-up implemented incorrectly.

## Other Disclaimers
Interfaces are liable to change on a whim, features will mostly be added as I need them.

## License

Licensed under either of

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

If for some reason you wish to contribute to this, any contribution intentionally
submitted for inclusion in this work by you, as defined in the Apache-2.0
license, shall be dual licensed as above, without any additional terms or
conditions.
