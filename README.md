# Awesome Haskell Lint [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome haskell linting tools, guides, and best practices.

## `hlint`

[`hlint`](https://hackage.haskell.org/package/hlint) is the currently most-used haskell linter.

It allows to specify 

- code rewrite suggestions (e.g. “`\x -> f x`, why not: `f`”)
- disallowed functions, symbols and modules

and comes with a range of builtin suggestions.

The validity of many builtin suggestions is debatable, thus they can be disabled in a `.hlint.yaml` file.
An example of such an ignore list: https://gist.github.com/Profpatsch/5a41d0283755d573511b08c01ff40148

### `hlint` rule sets

* [“hlint, the good parts”](https://gist.github.com/Profpatsch/5a41d0283755d573511b08c01ff40148)
* [“list of dangerous functions”](https://github.com/NorfairKing/haskell-dangerous-functions)

### Tutorials

TODO: link tutorials/blog posts


## `weeder`

[`weeder`](https://hackage.haskell.org/package/weeder) is a tool to detect dead code, by looking at the cabal `dist`/`dist-newstyle` directories.

TODO: link tutorials/blog posts

