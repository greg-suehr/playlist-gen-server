# CI Pipeline

An overview of this project's development pipeline.


## Automated tests

Build and run tests, or explicitly cache dependencies and run tests:

  > $ cargo test
  > $ cargo build; cargo test

Audit test coverage:

  > $ cargo tarpaulin --ignore-tests


## Linter

Run static analysis to fail on warns:

  > $ cargo clippy -- -D warnings

Run security audit:

  > $ cargo audit

Enforce standard formatting:

  > $ cargo fmt -- --check
  > $ cargo fmt