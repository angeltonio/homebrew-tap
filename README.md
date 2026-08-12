# homebrew-tap

Homebrew formulae for tools I maintain.

## Usage

```bash
brew tap angeltonio/tap
brew install <formula>
```

Or in one step, without tapping first:

```bash
brew install angeltonio/tap/<formula>
```

Note the missing `homebrew-` prefix in the tap name. Homebrew requires the
repository to be called `homebrew-tap` and then strips the prefix everywhere
you type it.

## Formulae

| Formula | Description |
| --- | --- |
| _(none published yet)_ | |

## About the contents of this repository

Everything under `Formula/` is generated. [GoReleaser](https://goreleaser.com)
writes each formula during a release, with the download URLs and checksums for
that exact version, and commits it here.

Editing a formula by hand will work until the next release overwrites it. Fix
the source project's release configuration instead.
