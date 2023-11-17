# Minigrep

A simple grep-like program written in Rust.

## Usage

`cargo run -- <query> <filename>`

A `poem.txt` is provided for testing.

To do a case insensitive search, set the `IGNORE_CASE` environment variable.

`IGNORE_CASE=1 cargo run -- <query> <filename>`

## Testing

`cargo test`
