# gpambrozio/homebrew-tap

Homebrew casks for my macOS apps.

```bash
brew install --cask gpambrozio/tap/paseo-menubar
```

## paseo-menubar

[Paseo Icon](https://github.com/gpambrozio/paseo-menubar) — a menu-bar indicator for
[Paseo](https://paseo.sh) workspaces. It shows which of your workspaces need input,
failed, are ready to review, or are still working, and opens one in Paseo when you
click it.

Apple Silicon only, macOS 12 or later. The app is signed and notarized, so Gatekeeper
opens it without a right-click-to-open dance.

`Casks/paseo-menubar.rb` is generated. It is published from
[`packaging/homebrew/paseo-menubar.rb`](https://github.com/gpambrozio/paseo-menubar/blob/main/packaging/homebrew/paseo-menubar.rb)
in the app's own repo by its `homebrew-cask` workflow, which checksums the dmg
it downloads from the release. Edit it there, not here — a change made in this
repo is overwritten by the next release.
