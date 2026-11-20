# Changelog

## [v0.2.2] - 2026-11-18
- Move the repository to the `serde-tools` GitHub organization.

## [v0.2.1] - 2026-04-24
- Expose `Serializer` and `Deserializer` directly (#17).
- Simplify the lifetimes and trait bounds of reader and writer parameters (#16).

## [v0.2.0] - 2026-04-01
- Depend on `serde_core` instead of `serde`, and remove the dependency on `thiserror` (#14).

## [v0.1.6] - 2023-10-12
- Add deserialization from a reader (`from_reader`) (#6).

## [v0.1.5] - 2023-02-15
- Support customized maximum container depths.

## [v0.1.4] - 2022-10-05
- Fix container-depth checks for enums, so that serialization and deserialization agree.
- Update the `serde` and `thiserror` dependencies.

## [v0.1.3] - 2021-05-18
- Allow `W: ?Sized` in `serialize_into<W, T>`.

## [v0.1.2] - 2020-12-14
- Improve the README.

## [v0.1.1] - 2020-12-11
- Renaming crate into "bcs".

## v0.1.0 - 2020-11-17
- Initial release (as `libra-canonical-serialization`).

[v0.2.2]: https://crates.io/crates/bcs/0.2.2
[v0.2.1]: https://crates.io/crates/bcs/0.2.1
[v0.2.0]: https://crates.io/crates/bcs/0.2.0
[v0.1.6]: https://crates.io/crates/bcs/0.1.6
[v0.1.5]: https://crates.io/crates/bcs/0.1.5
[v0.1.4]: https://crates.io/crates/bcs/0.1.4
[v0.1.3]: https://crates.io/crates/bcs/0.1.3
[v0.1.2]: https://crates.io/crates/bcs/0.1.2
[v0.1.1]: https://crates.io/crates/bcs/0.1.1
