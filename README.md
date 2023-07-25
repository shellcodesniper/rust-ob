# RUST-Obfuscator

## Instruction
> simply `wget "https://raw.githubusercontent.com/shellcodesniper/rust-ob/main/ob.py" -O ob.py` in package
1. place ob.py to ur package root
3. `pip3 install toml`
4. python3 ob.py
5. cd ./obfuscated/ && cargo publish

OR
1. `cargo install cargo-merge`
2. `cargo merge`
3. `cargo install cargo-merge && cargo merge && mkdir -p obfuscated/src && cp ./target/merge/merged.rs ./obfuscated/src/lib.rs && cp ./Cargo.toml ./obfuscated && cargo publish --allow-dirty --registry "YOUR_REGISTRY"`
