# homebrew-yonder

Homebrew tap for [Yonder](https://github.com/zacharytgray/yonder).

```sh
brew trust --cask zacharytgray/yonder/yonder
brew install --cask zacharytgray/yonder/yonder
```

Homebrew refuses to load casks from third-party taps until you trust them. The first line trusts
only the Yonder cask, which also lets `brew upgrade --cask yonder` work later.

The cask in `Casks/` is updated by Yonder's release workflow. Don't edit it by hand.
