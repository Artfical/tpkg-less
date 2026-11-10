# less

less 668, the pager

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install less
```

| | |
|---|---|
| Version | 668 |
| Licence | GPL-3.0-or-later OR BSD-2-Clause |
| Upstream | - |
| Needs | [`terminfo`](https://github.com/Artfical/tpkg-terminfo) |
| Needs tOS build | 619 or newer |
| Size | 183398 bytes (398448 unpacked) |
| SHA-256 of the `.tpkg` | `400ce8108adce4114dcb2269411009c2cb56fcf8f223df2d579f2640534be713` |

## Commands it adds

| Command | Runs |
|---|---|
| `less` | `bin/less` |
| `lessecho` | `bin/lessecho` |
| `lesskey` | `bin/lesskey` |

## Download

The package file (`less-668.tpkg`) and the sources it was built from are the assets of the
[v668 release](https://github.com/Artfical/tpkg-less/releases/tag/v668).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `less-668.tar.gz`

Check a download: `sha256sum less-668.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later OR BSD-2-Clause. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
