RustCoder

curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
or
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

source "$HOME/.cargo/env"

rustup install 1.70.0
rustup default 1.70.0

rustup --version
rustc --version
cargo --version
