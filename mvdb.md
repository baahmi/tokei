## build
cargo build --color=always --message-format=json-diagnostic-rendered-ansi --package tokei --lib
less verbose output :
cargo build --color=always --package tokei --lib