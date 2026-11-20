# Contributing to BCS

Development for `bcs` happens in the open on GitHub.

## Pull Requests

We actively welcome your pull requests. If you have a new feature in mind, please discuss the feature in an issue to
ensure that your contributions will be accepted.

1. Fork the repo and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes with `cargo test`.
5. Run `cargo fmt` to automatically format your changes, and `cargo clippy --all-targets` to check for warnings (CI
   rejects both formatting issues and warnings).
6. If you've changed the crate-level documentation in `src/lib.rs`, regenerate `README.md` with
   [`cargo readme`](https://crates.io/crates/cargo-readme): `cargo readme > README.md`.

## Issues

We use GitHub issues to track public bugs. Please ensure your description is clear and has sufficient instructions to be
able to reproduce the issue.

To report a security vulnerability, please do not file a public issue. See [SECURITY.md](SECURITY.md) instead.

## License

By contributing to `bcs`, you agree that your contributions will be licensed under the terms of the
[`LICENSE`](LICENSE) file in the root directory of this source tree.
