# sable-darwin-ci

Builds the nixpkgs `sable-desktop` package from a branch of
[LashaKamadadze/nixpkgs](https://github.com/LashaKamadadze/nixpkgs) on an
Apple Silicon GitHub runner, checks the app signature, starts the app and
takes a screenshot.

Run it from the Actions tab ("Run workflow"), or:

```
gh workflow run darwin.yml -R LashaKamadadze/sable-darwin-ci -f ref=sable-desktop-darwin
```

Set up with AI assistance (Claude Code).
