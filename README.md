# minigrep

## A simple `grep` clone in Rust

This little project is a simple clone for the famous `grep` command
line utility from UNIX operating systems.

The initial project code comes from the chapters 12 and 13 from [The
Rust Programming Language](https://doc.rust-lang.org/book/)
book. Additional code will extend its initial functionalities.


## Usage

To use `mingrep`, compile and run with `cargo`
```bash
cargo build --release
cargo run <QUERY> <FILENAME>
```

or install it and run it by its name
```bash
minigrep <QUERY> <FILENAME>
```

*res/* folder comes with "I'm nobody! Who are you?", a poem by Emily
Dickinson. It's meant to be a handy file to perform simple tests.


## Tests

Run tests with
```bash
cargo test
```
