# CommonsBase_Win32

`CommonsBase_Win32` packages Wine-based Windows support components for dk
workspaces.

The core package targets in this repository are:

- `CommonsBase_Win32.Lookup@1.0.0`
- `CommonsBase_Win32.Wine.Bundle@11.2.0`
- `CommonsBase_Win32.Wine@11.2.0`

`Wenv` is available as `CommonsBase_Win32.Wenv@0.1.0`.

This repository was bootstrapped from legacy package definitions copied into
`etc\dk\v`.

Local validation also expects sibling checkouts of `CommonsBase_GNU` and
`CommonsBase_Std` so the test comments can import their package definitions
instead of pretending they are local.
