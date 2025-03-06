# gh-clone-team-repos

A little `gh` extension I put together to help my team's members clone our
GitHub repositories in bulk. Not the prettiest, but it works for me so far.

## Getting started

Currently requires `fzf`.

Install the extension:

```shell
gh extension install ruralocity/gh-clone-team-repos
```

## Usage

```shell
gh clone-team-repos oreillymedia/publishing-engineering
```

Use fuzzy find to filter the returned list, then `<tab>` to toggle cloning that repository. Or select `Toggle All`. Press `<return>` to confirm your selections and complete the cloning.
