# Homebrew-AnchoreCTL

This repository contains the homebrew formula for the [anchorectl project](https://github.com/anchore/anchorectl)

To install anchorectl via homebrew, you'll need to export a github api token that has access to anchore/anchorectl and anchore/homebrew-anchorectl

```shell script
export HOMEBREW_GITHUB_API_TOKEN="XXXXX"
brew tap anchore/anchorectl
brew install anchorectl
```