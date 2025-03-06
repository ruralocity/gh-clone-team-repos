# gh-clone-team-repos

A little `gh` extension I put together to help my team's members clone our
GitHub repositories in bulk. Not the prettiest, but it works for me so far.
Maybe useful for you when onboarding new team members, or setting up a fresh
workstation. ChatGPT-4o was helpful.

## Getting started

Currently requires `fzf`. You'll get yelled at if it's missing. And, of course,
`gh`.

Install the extension:

```shell
gh extension install ruralocity/gh-clone-team-repos
```

## Usage

```shell
gh clone-team-repos oreillymedia/publishing-engineering
```

Use fuzzy find to filter the returned list, then `<tab>` to toggle cloning that repository. Or select `Toggle All`. Press `<return>` to confirm your selections and complete the cloning.

## Future considerations

- I did this in a hurry. I'm interested in using [Bubble Tea] for fun TUI apps. So this may get re-written at some point.

[Bubble Tea]:https://github.com/charmbracelet/bubbletea
