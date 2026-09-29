# kirg0/homebrew-tap

Homebrew tap for [d9c](https://github.com/kirg0/d9c) — a terminal UI for managing Docker on
remote hosts over TCP or SSH.

```sh
brew install kirg0/tap/d9c     # = brew tap kirg0/tap && brew install d9c
brew upgrade d9c
```

The formula installs the prebuilt release binary for macOS (Intel / Apple Silicon) and Linux
(x86-64 / ARM64).

`Formula/d9c.rb` is generated and committed automatically by the
[d9c release workflow](https://github.com/kirg0/d9c/blob/main/.github/workflows/release.yml)
on every release — do not edit it by hand.
