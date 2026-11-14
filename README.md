# Flapdot releases

Downloads for [Flapdot](https://flapdot.com), a dot-matrix widget app for macOS.

### [Download the latest version →](https://flapdot.com/download)

Every release here carries one file: `Flapdot-<version>.dmg`, signed with a Developer ID
certificate and notarized by Apple. Flapdot updates itself from these releases, so there
is normally nothing to download by hand — this repository is where the app looks.

## Requirements

- macOS 14 Sonoma or later
- Apple silicon or Intel

## Verifying a download

```sh
spctl -a -t open --context context:primary-signature -v Flapdot-<version>.dmg
```

Apple's check should answer `accepted` and `source=Notarized Developer ID`.

## About this repository

It holds release downloads and release notes, nothing else. Flapdot's source code lives
in a separate private repository, and no signing keys or credentials are published here.

Questions, problems or a lost licence key: **hello@flapdot.com**
