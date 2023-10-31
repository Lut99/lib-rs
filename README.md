# lib-rs
A collection of Rust libraries that are useful across (my) projects.


## Libraries
The following libraries are part of this project:
- [ast-toolkit-rs](https://github.com/Lut99/ast-toolkit-rs): A collection of structs and interfaces extremely useful when working with compilers that parse text into ASTs.
- [bytes-rs](https://github.com/Lut99/bytes-rs): Adds a Rust derive macro that can be used to easily parse & serialize header-like bytes that have specified order and interpretation.
- [enum-debug](https://github.com/Lut99/enum-debug): Simple Rust crate that implements EnumDebug, which can automatically derive a formatter for enum variant names only.
- [error-trace-rs](https://github.com/Lut99/error-trace-rs): Small Rust crate for printing nice errors traits based on [`Error::source()`].
- [humanlog-rs](https://github.com/Lut99/humanlog-rs): A simple logger for the [log](https://https://docs.rs/log/latest/log/) crate that aims to have a simple user mode and a comprehensive debug mode.
- [serializable-rs](https://github.com/Lut99/serializable-rs): Provides a helper trait for [serde](https://serde.rs) types that makes working with them slightly nicer.
- [transform-rs](https://github.com/Lut99/transform-rs): A small Rust library that defined the `TransformIter`-iterator, which can map an element in a tuple to zero or more elements of a potentially different type.


## Usage
See each library in detail for how to use them. In general, just add them to your `Cargo.toml` and you should be fine.


## License
Each library has its own license. Check out their repositories for more information.
