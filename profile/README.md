<p align="center">
  <img src="https://raw.github.com/pest-parser/pest/master/pest-logo.svg?sanitize=true" width="80%"/>
</p>

# pest. The Elegant Parser

[![Join the chat at https://gitter.im/pest-parser/pest](https://badges.gitter.im/dragostis/pest.svg)](https://gitter.im/pest-parser/pest?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Book](https://img.shields.io/badge/book-WIP-4d76ae.svg)](https://pest.rs/book)
[![Docs](https://docs.rs/pest/badge.svg)](https://docs.rs/pest)

[![pest Continuous Integration](https://github.com/pest-parser/pest/actions/workflows/ci.yml/badge.svg)](https://github.com/pest-parser/pest/actions/workflows/ci.yml)
[![codecov](https://codecov.io/gh/pest-parser/pest/branch/master/graph/badge.svg)](https://codecov.io/gh/pest-parser/pest)
<a href="https://blog.rust-lang.org/2021/11/01/Rust-1.56.1.html"><img alt="Rustc Version 1.56.1+" src="https://img.shields.io/badge/rustc-1.56.1%2B-lightgrey.svg"/></a>

[![Crates.io](https://img.shields.io/crates/d/pest.svg)](https://crates.io/crates/pest)
[![Crates.io](https://img.shields.io/crates/v/pest.svg)](https://crates.io/crates/pest)

pest is a general purpose parser written in Rust with a focus on accessibility,
correctness, and performance. It uses parsing expression grammars
(or [PEG]) as input, which are similar in spirit to regular expressions, but
which offer the enhanced expressivity needed to parse complex languages.

[PEG]: https://en.wikipedia.org/wiki/Parsing_expression_grammar

## Getting started

The recommended way to start parsing with pest is to read the official [book].

Other helpful resources:

* API reference on [docs.rs]
* play with grammars and share them on our [fiddle]
* find previous common questions answered or ask questions on [GitHub Discussions]
* leave feedback, ask questions, or greet us on [Gitter] or [Discord]

[book]: https://pest.rs/book
[docs.rs]: https://docs.rs/pest
[fiddle]: https://pest.rs/#editor
[Gitter]: https://gitter.im/pest-parser/pest
[Discord]: https://discord.gg/XEGACtWpT2
[GitHub Discussions]: https://github.com/pest-parser/pest/discussions

## Repositories
The pest-parser GitHub organization hosts several repositories.
The main one is naturally [pest](https://github.com/pest-parser/pest)
where you can find the source code of main pest-related crates.

The [pest.rs](https://pest.rs) website is spanned across two repositories:
* [book](https://github.com/pest-parser/book) contains the source code
for building the [book on pest.rs](https://pest.rs/book).
* [site](https://github.com/pest-parser/site) contains the source code
for bundling the book with the rest of the website source code (both
the playground and the homepage)

There are two tooling-related pest crates:
* [pest-fmt](https://github.com/pest-parser/pest-fmt) can help to format
pest grammars (you can try it in this cool [online version](https://sbeckeriv.github.io/pest_format/)).
* [ast](https://github.com/pest-parser/ast) can help to reduce boilerplate
when converting pest parse trees to abstract syntax trees
(BTW the [pest_consume](https://crates.io/crates/pest_consume) crate can also
help with the parse tree traversing boilerplate).

There are editor plugins for pest:

* [pest.vim](https://github.com/pest-parser/pest.vim) can do syntax highlighting
of pest grammars in Vim.
* [intellij-pest](https://github.com/pest-parser/intellij-pest) can do syntax highlighting,
completion, refactoring (renaming, extracting rules, inlining) in IntelliJ editors, such as
IDEA or CLion, of pest grammars in both external files and in ones embedded in Rust.
* [vscode-pest](https://marketplace.visualstudio.com/items?itemName=pest.pest-ide-tools) Pest support for VS Code, via the LSP.

Finally, [pest3](https://github.com/pest-parser/pest3) contains an unfinished effort
of pest 3.0 that is stalled for now. You can follow the [future progress on this milestone here](https://github.com/pest-parser/pest/milestone/6): feel free to comment on its issues
or open a discussion thread.

## Projects using pest

* [pest_meta](https://github.com/pest-parser/pest/blob/master/meta/src/grammar.pest) (bootstrapped)
* [AshPaper](https://github.com/shnewto/ashpaper)
* [brain](https://github.com/brain-lang/brain)
* [cicada](https://github.com/mitnk/cicada)
* [comrak](https://github.com/kivikakk/comrak)
* [elastic-rs](https://github.com/cch123/elastic-rs)
* [graphql-parser](https://github.com/Keats/graphql-parser)
* [handlebars-rust](https://github.com/sunng87/handlebars-rust)
* [hexdino](https://github.com/Luz/hexdino)
* [Huia](https://gitlab.com/jimsy/huia/)
* [insta](https://github.com/mitsuhiko/insta)
* [jql](https://github.com/yamafaktory/jql)
* [json5-rs](https://github.com/callum-oakley/json5-rs)
* [mt940](https://github.com/svenstaro/mt940-rs)
* [Myoxine](https://github.com/d3bate/myoxine)
* [py_literal](https://github.com/jturner314/py_literal)
* [rouler](https://github.com/jarcane/rouler)
* [RuSh](https://github.com/lwandrebeck/RuSh)
* [rs_pbrt](https://github.com/wahn/rs_pbrt)
* [stache](https://github.com/dgraham/stache)
* [tera](https://github.com/Keats/tera)
* [ui_gen](https://github.com/emoon/ui_gen)
* [ukhasnet-parser](https://github.com/adamgreig/ukhasnet-parser)
* [ZoKrates](https://github.com/ZoKrates/ZoKrates)
* [Vector](https://github.com/timberio/vector)
* [AutoCorrect](https://github.com/huacnlee/autocorrect)
* [yaml-peg](https://github.com/aofdev/yaml-peg)
* [qubit](https://github.com/abhimanyu003/qubit)
* [caith](https://github.com/Geobert/caith) (a dice roller crate)
* [Melody](https://github.com/yoav-lavi/melody)
