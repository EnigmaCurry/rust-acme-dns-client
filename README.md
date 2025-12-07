# rust-acme-dns-client

[![Crates.io](https://img.shields.io/crates/v/rust-acme-dns-client?color=blue
)](https://crates.io/crates/rust-acme-dns-client)
[![Coverage](https://img.shields.io/badge/Coverage-Report-purple)](https://enigmacurry.github.io/rust-acme-dns-client/coverage/master/)


## Install

[Download the latest release for your platform.](https://github.com/enigmacurry/rust-acme-dns-client/releases)

Or install via cargo ([crates.io/crates/rust-acme-dns-client](https://crates.io/crates/rust-acme-dns-client)):

```
cargo install rust-acme-dns-client
```

### Tab completion

To install tab completion support, put this in your `~/.bashrc` (assuming you use Bash):

```
### Bash completion for rust-acme-dns-client (Put this in ~/.bashrc)
source <(rust-acme-dns-client completions bash)
```

If you don't like to type out the full name `rust-acme-dns-client`, you can make
a shorter alias (`h`), as well as enable tab completion for the alias
(`h`):

```
### Alias rust-acme-dns-client as h (Put this in ~/.bashrc):
alias h=rust-acme-dns-client
complete -F _rust-acme-dns-client -o bashdefault -o default h
```

Completion for Zsh and/or Fish has also been implemented, but the
author has not tested this:

```
### Zsh completion for rust-acme-dns-client (Put this in ~/.zshrc):
autoload -U compinit; compinit; source <(rust-acme-dns-client completions zsh)

### Fish completion for rust-acme-dns-client (Put this in ~/.config/fish/config.fish):
rust-acme-dns-client completions fish | source
```

## Usage

```
$ rust-acme-dns-client

Usage: rust-acme-dns-client [OPTIONS] [COMMAND]

Commands:
  hello        Greeting
  completions  Generates shell completions script (tab completion)
  help         Print this message or the help of the given subcommand(s)

Options:
      --log <LEVEL>  Sets the log level, overriding the RUST_LOG environment variable. [possible values: trace, debug, info, warn, error]
  -v                 Sets the log level to debug.
  -h, --help         Print help
  -V, --version      Print version
```

## Development

See [DEVELOPMENT.md](DEVELOPMENT.md)
