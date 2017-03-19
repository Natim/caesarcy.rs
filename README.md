# caesarlib
Caesar cipher capabilities for Rust.<br>
[![Current Version](http://meritbadge.herokuapp.com/caesarlib)](https://crates.io/crates/caesarlib)
[![Build Status](https://travis-ci.org/caesarlib/caesarlib.rs.svg)](https://travis-ci.org/caesarlib/caesarlib.rs)

## Usage
Add this to your `Cargo.toml`:

```toml
[dependencies]
caesarlib = "0.1.1"
```

and this to your crate root:

```rust
extern crate caesarlib;

use caesarlib::*;
```

## Methods
```rust
fn encipher(offset: i32, message: &str) -> String;

fn decipher(offset: i32, message: &str) -> String;
```

## Author
* [Lukas Mueller](https://crates.io/crates/caesarlib)

## Background
This was inspired by my [Caesar Cipher algorithm
implentation in Swift](https://github.com/luki/caesarlib/blob/master/Caesar/Algorithms.swift) used in my [iOS application caesarlib](https://github.com/luki/caesarlib)
