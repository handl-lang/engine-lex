# tool-lex

The lex-operation contract: `LexerEngine`, `LexerRequest`, `Lexer`.

## What it is

The **abstraction crate** for the lex operation (ADR-0044 §1, §3): the
`LexerEngine` trait, the `LexerRequest` describing what to tokenize, and a
`Lexer` handle. It contains **no lexing logic** — the data-driven implementation
is `tool-lex-pattern`.

## Start here

- **Reference** — [public API](/tool-lex/reference/)
- **How-to** — [task recipes](/tool-lex/how-to/)
- **Explanation** — [design and rationale](/tool-lex/explanation/)

No tutorials: this repo is a building block used from Rust. End-to-end
walkthroughs live with the product that composes it — see the
[Handl platform](/handl/).
