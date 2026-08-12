# homebrew-tap

Homebrew casks for tools I maintain.

## Usage

```bash
brew tap angeltonio/tap
brew install <cask>
```

Or in one step, without tapping first:

```bash
brew install angeltonio/tap/<cask>
```

Note the missing `homebrew-` prefix in the tap name. Homebrew requires the
repository to be called `homebrew-tap` and then strips the prefix everywhere
you type it.

## Casks

| Cask | Description |
| --- | --- |
| [aliasdeck](https://github.com/angeltonio/aliasdeck) | Your commands. Every machine. Compiles neutral aliases into shell-specific syntax. |

## About the contents of this repository

Everything under `Casks/` is generated. [GoReleaser](https://goreleaser.com)
writes each cask during a release, with the download URLs and checksums for
that exact version, and commits it here.

Editing a cask by hand will work until the next release overwrites it. Fix
the source project's release configuration instead.
