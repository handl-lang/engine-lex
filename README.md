# engine-lex

`hnl-engine-lex` — the abstraction crate for the lex operation.

An `engine-*` crate: the trait/type surface for tokenization that concrete
lexer engines (`engine-lex-pattern`) implement.

## Development

```bash
cargo xtask gate        # fmt --check → clippy -D warnings → test → doc
```

`cargo xtask` wraps the repo's `xtask/` crate (`fmt`, `clippy`, `test`, `doc`,
`check`, `gate`); `ci.sh` is the gate entry. Deps resolve from git, so no
sibling checkouts are needed; a plain clone test-runs as-is.

## License

MIT.

## Documentation

<https://handl-lang.github.io/docs/engine-lex/>
