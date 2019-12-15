# MD Link Linter Github Action

This action iterates through all folders in given path, looking for markdown files trying to detect invalid/outdated links.

## Inputs

### `path`

**Required** Path in which md link linter should start looking for markdown files

## Outputs

none

## Example usage

```yaml
uses: norberttech/md-link-linter-action@v1
with:
  path: '.'
```