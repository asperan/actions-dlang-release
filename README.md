# dlang-release

This action creates a release with a new tag and the changelog from the last tag.

## Inputs

### `token`
**Required** The token to use to create the release.

### `branch`
The branch to use to create the release. Default `"main"`.

### `is-executable`
Whether the project builds an executable file. Default `false`.
