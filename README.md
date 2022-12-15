Expected error

```
✗ cargo build
    Updating crates.io index
error: failed to select a version for `signature`.
    ... required by package `rustcrypto-dep-hell-example v0.1.0 (/Users/code/deps)`
versions that meet the requirements `^1.6.0` are: 1.6.4, 1.6.3, 1.6.2

all possible versions conflict with previously selected packages.

  previously selected package `signature v1.3.2`
    ... which satisfies dependency `signature_1_3_1 = "=1.3.2"` of package `rustcrypto-dep-hell-example v0.1.0 (/Users/code/deps)`
```
