# `export-git-proof` GitHub Action

Export proof of the state of a git repo

Usage:

```yaml
- name: Checkout
  uses: actions/checkout@v4
  with:
    fetch-depth: 0

- name: Install
  uses: japgolly/export-git-proof@main
  env:
    GITHUB_TOKEN: ${{ secrets.GIST_TOKEN }}
  with:
    gist_id: YOUR_GIST_ID
```
