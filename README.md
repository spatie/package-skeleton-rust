# {{crate_name}}

{{description}}

[![CI](https://github.com/{{owner}}/{{repository}}/actions/workflows/ci.yml/badge.svg)](https://github.com/{{owner}}/{{repository}}/actions/workflows/ci.yml)
[![Crates.io](https://img.shields.io/crates/v/{{crate_name}}.svg)](https://crates.io/crates/{{crate_name}})
[![Docs.rs](https://docs.rs/{{crate_name}}/badge.svg)](https://docs.rs/{{crate_name}})

<!-- skeleton:start -->
## Create a package

Use this template, then run `python3 configure.py` (Windows: `py -3 configure.py`). Requires Python 3.11+ for configuration and [Rust](https://rustup.rs/) 1.89+ for the library. The script asks for the crate name, GitHub repository, author and description, then replaces placeholders and removes itself. See [SKELETON.md](SKELETON.md) for template maintenance and non-interactive use.

<!-- skeleton:end -->
## Installation

Requires Rust 1.89 or newer. Once the crate is published:

```sh
cargo add {{crate_name}}
```

Before publication, use a path dependency from a neighboring application:

```toml
[dependencies]
{{crate_name}} = { path = "../{{repository}}" }
```

## Usage

```rust
use {{crate_import}}::greet;

assert_eq!(greet("Freek"), "Hello, Freek!");
```

See the [usage guide](https://github.com/{{owner}}/{{repository}}/blob/main/docs/usage.md) and [PHP parity notes](https://github.com/{{owner}}/{{repository}}/blob/main/PARITY.md).

## Support us

We invest a lot of resources into creating [open source packages](https://spatie.be/open-source). You can support us by [buying one of our paid products](https://spatie.be/open-source/support-us).

We also appreciate postcards from your hometown. You'll find our address on [our contact page](https://spatie.be/about-us).

## Testing

```sh
cargo test --locked --all-targets --all-features
cargo test --locked --doc --all-features
```

See [all quality checks](https://github.com/{{owner}}/{{repository}}/blob/main/docs/testing.md). The README and Markdown guides are tested by rustdoc, including setup on hidden `# ` lines.

## Changelog

See [CHANGELOG.md](https://github.com/{{owner}}/{{repository}}/blob/main/CHANGELOG.md).

## Contributing

See [CONTRIBUTING.md](https://github.com/{{owner}}/{{repository}}/blob/main/CONTRIBUTING.md) and the [Rust API Guidelines](https://rust-lang.github.io/api-guidelines/).

## Security

Report vulnerabilities privately using the instructions in [SECURITY.md](https://github.com/{{owner}}/{{repository}}/blob/main/SECURITY.md).

## Credits

- [{{author_name}}](https://github.com/{{author_username}})
- [All contributors](https://github.com/{{owner}}/{{repository}}/graphs/contributors)

## License

The MIT License (MIT). See [LICENSE.md](https://github.com/{{owner}}/{{repository}}/blob/main/LICENSE.md).
