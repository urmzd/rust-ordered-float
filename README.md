# Ordered Floats

Provides several wrapper types for Ord and Eq implementations on f64.

See the [API documentation](https://docs.rs/ordered-float) for further details.

## no_std

To use `ordered_float` without requiring the Rust standard library, disable
the default `std` feature:

```toml
[dependencies]
ordered-float = { version = "3.0", default-features = false }
```

## Optional features

The following optional features can be enabled in `Cargo.toml`:

* `rand`: Adds implementations for various distribution types provided by the `rand` crate.
* `serde`: Implements the `serde::Serialize` and `serde::Deserialize` traits.
* `schemars`: Implements the `schemars::JsonSchema` trait.
* `proptest`: Implements the `proptest::Arbitrary` trait.

## License

MIT
