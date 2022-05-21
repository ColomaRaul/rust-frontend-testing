# Improve a Rust program to develop a simple Frontend (with Yew)

Installing [trunk](https://crates.io/crates/trunk/0.9.1) packages
```bash
cargo install trunk
```

Install component [package](https://doc.rust-lang.org/nightly/nightly-rustc/rustc_target/spec/wasm32_unknown_unknown/index.html#:~:text=The%20wasm32%2Dunknown%2Dunknown%20target,when%20using%20the%20standard%20library.)
```bash
rustup target up add wasm32-unknown-unknown
```

Run server
```bash
trunk serve
```

And navigate to localhost:8080