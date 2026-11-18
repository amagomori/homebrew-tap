# homebrew-tap

A [Homebrew](https://brew.sh) tap for [Trident](https://github.com/amagomori/trident), a fast GPU-rendered terminal emulator.

## Install Trident

- To install in one step, run `brew install --cask amagomori/tap/trident`.
- Or tap this repository first, then install:

  ```sh
  brew tap amagomori/tap
  brew install --cask trident
  ```

To update, run `brew upgrade`.

## Cask maintenance

Trident's release workflow (`release.py packages`) generates and pushes `Casks/trident.rb` for every
stable tag, so don't edit it by hand. The builds are ad-hoc signed, so
`audit_exceptions/signing_audit_skiplist.json` exempts `trident` from the signing audit.
