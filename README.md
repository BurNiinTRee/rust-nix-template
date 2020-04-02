# Rust Nix Template
This is a Rust project developed using Cargo and Nix.

## Building
### Using Nix
To build this project you need a working installation of [Nix].
```
$ nix build
```

### Using Cargo
Alternatively this project can also be built using a global [Rust] installation.
```
$ cargo build
```
or
```
$ cargo build --release
```

## Development
For a fully reproducible environment please use [Nix] in conjuction with [Direnv] and [Lorri].

The environment can be managed using [Niv].


[Rust]: https://rustup.rs
[Nix]: https://nixos.org/nix/
[Direnv]: https://github.com/direnv/direnv
[Lorri]: https://github.com/target/lorri
[Niv]: https://github.com/nmattia/niv
