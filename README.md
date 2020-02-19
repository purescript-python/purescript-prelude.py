## PureScript-Prelude For Python

Following https://github.com/purescript/purescript-prelude , we provide
corresponding Python FFI files.

If the purescript library is not distributed with required Python FFI files,
the PSPY compiler will then try to get them from the repo [PureScript Python FFI Index](https://github.com/purescript-python/purescript-python-ffi-index) by default.

You can also make your own index repo to use another `Prelude` Python implementation, by following the structure of
[PureScript Python FFI Index](https://github.com/purescript-python/purescript-python-ffi-index).
