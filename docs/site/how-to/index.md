# How-to guides

Task recipes. Each assumes sibling checkouts of this repo and of the platform
repos it patches.

## Implement a lexer

Implement `LexerEngine`; return tokens plus the advanced position. Keep policy — patterns, priority, block forms — in `Language` data rather than in the engine, as `engine-lex-pattern` does.
