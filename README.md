# NUCCDC Tools 🔧

## Repo Structure

- `unix`: Unix tools
- `windows`: Windows tools
- More to come?

## Contributing

Make pull requests to `develop` branch. PRs require 1 approving review before merging. 

## Freezing and Submitting to CCDC

When the deadline is reached for submitting to CCDC, tag the latest `develop` commit and 
create a release on GitHub.

```sh
git tag YYYY-eventname
git push --tags
```

To download the released version, you can download the source through the release:

e.g.
```
git tag 2021-qualifiers
git push --tags 
# Create github release with the 2021-qualifiers tag

# These archives will then be available:
wget https://github.com/nuccdc/tools/archive/2021-qualifiers.tar.gz
wget https://github.com/nuccdc/tools/archive/2021-qualifiers.zip
```
