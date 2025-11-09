# minimal-reproduction-template

Reproduction for the [Renovate discussion 39139](https://github.com/renovatebot/renovate/discussions/39139).

## Current behavior

Renovate bumps up application version, f.e. from package.json or Chart.yaml and I want to know if the new version of the application is available somewhere, to be used in PR title.

## Expected behavior

New application version is available for usage in PR title. The version I am looking for is in line 3 of [package.json](package.json) in PR created by Renovate.

I am looking for option to set Pr title to: "chore: bump new_renovate to 1.0.1".


## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/39139