# cz-simple-changelog

A cloned and simplefied version of [cz-conventional-changelog](https://github.com/commitizen/cz-conventional-changelog). Simplified prompts for [conventional changelog](https://github.com/conventional-changelog/conventional-changelog) standard.

## Conventional and simplified
As conventional changelog is the preferred way to go (and the way I roll), this is a package for those who wants to follow, but think there is too much options in the types section.

This package uses all relevant types - those that goes on CHANGELOG.md - and sums all others in a single type, `chore`. So, if you need to do a build, test, refactor, etc; you just use the type as a scope: chore(build).

### Comparison table
cz-conventional-changelog | cz-simple-changelog
--|--
feat | feat
fix | fix
docs | 
style | 
refactor | 
perf | perf
test | 
build | 
ci | 
chore | chore
revert | revert
