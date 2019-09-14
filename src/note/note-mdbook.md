# mdBook

- https://github.com/rust-lang-nursery/mdBook
- [ユーザーガイド](https://rust-lang-nursery.github.io/mdBook/)

~~~bash
$ source ~/.cargo/env
.
~~~

~~~bash
$ cargo install mdbook
.
~~~

## 使い方

## mkbook serve

~~~bash
$ mdbook serve

2019-09-14 20:59:38 [INFO] (mdbook::book): Book building has started
2019-09-14 20:59:38 [INFO] (mdbook::book): Running the html backend
2019-09-14 20:59:40 [INFO] (mdbook::cmd::serve): Serving on: http://localhost:3000
2019-09-14 20:59:40 [INFO] (ws): Listening for new connections on [::1]:3001.
2019-09-14 20:59:40 [INFO] (mdbook::cmd::watch): Listening for changes...
~~~

## book.toml

- [TOML仕様の和訳](https://qiita.com/minoritea/items/c0de47b8beb813c655d4)

~~~toml
[book]
title = "The Rust Programming Language"
author = "Steve Klabnik and Carol Nichols, with Contributions from the Rust Community"

[output.html]
additional-css = ["ferris.css", "theme/2018-edition.css"]
additional-js = ["ferris.js"]
~~~

## 記事

- [eom/bookの日本語版を作り始めた](https://qiita.com/termoshtt/items/13965b57c2a4afa85399)
