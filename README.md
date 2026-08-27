# Homebrew tap for Okmate

```sh
brew install --cask koliyo/okmate/okmate
```

Homebrew 6 will not load a third-party tap until it is trusted. The
fully qualified name trusts only this cask. To trust the whole tap:

```sh
brew tap koliyo/okmate
brew trust koliyo/okmate
brew install --cask okmate
```

The cask installs [`Okmate.zip`](https://github.com/koliyo/okmate/releases)
from GitHub Releases (the same archive Sparkle serves), then links
`$(brew --prefix)/bin/okmate` to the bundle CLI. `auto_updates` is set so
Homebrew does not fight in-app Sparkle updates.

Cask versions are bumped by `okmate-ops promote tag vX.Y.Z` in
[koliyo/okmate](https://github.com/koliyo/okmate).
