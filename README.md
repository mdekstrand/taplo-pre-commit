# taplo pre-commit hook

This repo provides a pre-commit hook to format Toml files with Taplo, using the
binaries published to NPM for fast installation.  It is heavily inspired by
[nikaro's hooks](https://github.com/nikaro/taplo-pre-commit) — basically a
straight port to installing with `npm` instead of rebuilding the Rust source
from scratch.