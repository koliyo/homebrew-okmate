# Homebrew tap for Okmate

```sh
brew tap koliyo/okmate
brew install --cask okmate
```

The cask installs [`Okmate.zip`](https://github.com/koliyo/okmate/releases)
from GitHub Releases (the same archive Sparkle serves), then links
`$(brew --prefix)/bin/okmate` to the bundle CLI. `auto_updates` is set so
Homebrew does not fight in-app Sparkle updates.

Cask versions are bumped by `okmate-ops promote tag vX.Y.Z` in
[koliyo/okmate](https://github.com/koliyo/okmate).
