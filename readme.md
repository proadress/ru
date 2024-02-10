cargo install cargo-watch

## dev
cargo watch -x run

## dev wait 5s hot reload
cargo watch -s 'sleep 5 && cargo run'


## run
cargo run