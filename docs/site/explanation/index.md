# Explanation

## Why this crate exists

Lexing is the first place a language definition has to *be* data: token shapes
are declared per language and swapping the lexer must be a data change, not a
recompile. The abstraction is deliberately tiny so alternative lexers
(regex-based, hand-rolled, streaming) stay possible.

## Where it sits

This crate belongs to the `engine-*` family. Plugins, kits and hosts reach it
through the kit's operation slot, so the engine can be swapped without touching a
language definition.

See the [reference](/engine-lex/reference/) for the API and the
[how-to guides](/engine-lex/how-to/) for tasks.
