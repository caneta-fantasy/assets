# caneta-fantasy / assets

Public assets for the **caneta-fantasy** project. The code repos
(`fantasy-football`, `fantasy-docs`) are **private**, so images referenced from
their pull requests and docs can't be hotlinked from those repos — GitHub's
image proxy can't authenticate to a private repo. This public repo is the host
for such assets.

## Usage

Commit an asset, then reference it from a private repo's PR/markdown by an
**absolute raw URL pinned to the commit SHA** (so it keeps rendering after
branches move or are deleted):

```md
![alt](https://raw.githubusercontent.com/caneta-fantasy/assets/<commit-sha>/screenshots/<topic>/<name>.png)
```

## Layout

- `screenshots/<YYYY-MM>-<topic>/` — PR screenshots for a work item.

Only non-sensitive assets belong here — everything committed is public.
