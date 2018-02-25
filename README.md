# easy-changelog

Changelog helper to reduce resistance to communicating changes about your software

## Usage

```sh
> ./easy_changelog -h
usage: easy_changelog [-h] {prepare,release} ...

Changelog update utility.

optional arguments:
  -h, --help         show this help message and exit

Commands:
  {prepare,release}  subcomand to run
```

### Prepare

Create `CHANGELOG.md` from template by inserting project owner and project name into the document.

### Release

Create a new release entry with supplied version in the `CHANGELOG.md`. Updates unreleased reference and will create a comparison to the last known release.
