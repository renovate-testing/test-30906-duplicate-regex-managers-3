# 30906

Reproduction for [Renovate issue 30906](https://github.com/renovatebot/renovate/discussions/30906).

## Current behavior

Renovate increases the number of dependencies in the repository after each run customManagers process the same file.
Renovate may crash if the number of dependencies becomes large.

## Expected behavior

The number of dependecies should remain the same after subsequent runs.
