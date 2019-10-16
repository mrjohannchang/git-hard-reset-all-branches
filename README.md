# git-hard-reset-all

This small tool resets all your local branches to corresponding remote tracking branches.
Inspired by [Reset all branches of a local repo to be the same as remote](https://stackoverflow.com/questions/36019381/reset-all-branches-of-a-local-repo-to-be-the-same-as-remote).

## Usage

```
git hard-reset-all
```

Example output:

```
master
dev
  10c527f Patchset 2
  -> d32a2f6 Patchset 1
hotfix
  skipped: upstream is absent
```

## Installation

Copy `git-hard-reset-all` to your `$PATH` (such as `~/bin`).

## License

[Mozilla Public License Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)
