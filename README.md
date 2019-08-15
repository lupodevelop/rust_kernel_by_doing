# README

I'm following this excellent blog:  [os.phil-opp](https://os.phil-opp.com/) 

## NEED

* Work with nightly Rust
```
rustup toolchain install nightly

rustup default nightly
```
* Install Cargo xbuild
```
cargo install cargo-xbuild
```

* Install rust-src
```
rustup component add rust-src
```

* Use *xbuild* instead of *build*
```
cargo xbuild --target x86_64-custom.json
```