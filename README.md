# `export-git-proof` GitHub Action

Export proof of the state of a git repo

Usage:

```yaml
- name: Checkout
  uses: actions/checkout@v4
  with:
    fetch-depth: 0

- name: Export git proof
  uses: japgolly/export-git-proof@main
  with:
    token: ${{ secrets.GIST_TOKEN }}
    gist_id: YOUR_GIST_ID
```
