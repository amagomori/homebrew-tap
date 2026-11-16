# amagomori/homebrew-tap

Homebrew tap for [Trident](https://github.com/amagomori/trident), a fast GPU-rendered terminal emulator.

```sh
brew install --cask amagomori/tap/trident
```

Or `brew tap amagomori/tap` once, then `brew install --cask trident`. `brew upgrade` picks up new releases.

`Casks/trident.rb` is generated and pushed by Trident's release workflow (`release.py packages`) for every stable tag, so don't edit it by hand. Builds are ad-hoc signed only, so `audit_exceptions/signing_audit_skiplist.json` skips the signing audit for `trident`.
