# gh-split-pr

\_being a gh extension that splits huge PR in several PRs

## install

```
gh extension install kalak-io/gh-split-pr
```

## run

```
# Split a PR with default settings (25 files per PR, grouped by directory)
$ gh split-pr <pr-number>

# Split a PR with custom settings
$ gh split-pr <pr-number> --max-files=15 --group-by=extension

# See help
$ gh split-pr --help
```
