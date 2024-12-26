# gba-coretests

Rust's `coretests` test suite, configured to run on the GBA.

This test suite uses the [`gba_test`](https://github.com/Anders429/gba_test) testing framework. All of the tests themselves are copied from [rust/library/core/tests](https://github.com/rust-lang/rust/tree/master/library/core/tests). Some tests are omitted; specifically, tests relying on `std` and tests that are too large (mainly those that are also omitted or altered on `miri` runs) are not included.
