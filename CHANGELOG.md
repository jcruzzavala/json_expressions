### v0.7.2 [view commit logs](https://github.com/chancancode/json_expressions/compare/0.7.1...0.7.2)

* Bugfix: Corrected a misbehaving require statement in minitest helpers (Fixes #2)

### v0.7.1 [view commit logs](https://github.com/chancancode/json_expressions/compare/0.7.0...0.7.1)

* Bugfix: Correctly matching `false` inside a symbol-keyed hash (Fixes #1)

### v0.7.0 [view commit logs](https://github.com/chancancode/json_expressions/compare/0.6.0...0.7.0)

* BREAKING: Removed support for Object#match in favor of Object#===
* BREAKING: Removed configuration option JsonExpressions::Matcher.skip_match_on

### v0.6.0 [view commit logs](https://github.com/chancancode/json_expressions/compare/0.5.0...0.6.0)

* Added non-bang version of `strict`, `forgiving`, `ordered` and `unordered`
* Added RSpec support (thanks @bobthecow for the [initial implementation](https://gist.github.com/3086558))
* Added support for `Symobl` hash keys
* Switched examples in README to use `Symbol` hash keys
* Improved error messages

### v0.5.0

* Initial release