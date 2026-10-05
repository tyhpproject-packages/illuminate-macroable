<!-- tyhp-readme:start -->
# tyhpdef/illuminate-macroable

Tyhp type definitions for `illuminate/macroable` `13.32.0`.

```bash
composer require --dev tyhpdef/illuminate-macroable:13.32.0
```

This is a metapackage. Composer also installs `tyhpdef/illuminate-macroable-impl` (type files).
Require **this** name, not `tyhpdef/illuminate-macroable-impl`.

See https://tyhplang.com.

## Maintain `illuminate/macroable`? Ship the types yourself

If you are a Packagist maintainer of `illuminate/macroable`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/illuminate-macroable-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `illuminate/macroable` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/illuminate-macroable": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `illuminate/macroable` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `illuminate/macroable` with a real constraint,
   `"replace": { "tyhpdef/illuminate-macroable": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `illuminate/macroable` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/illuminate-macroable` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
