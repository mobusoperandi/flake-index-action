A GitHub Action.

Makes a GitHub Release.

The description of the release includes an index of the flake.

The index is obtained using `nix flake show`.

The title is "Flake index".

Not configurable.

Example:

```yaml
on:
  push:
    branches: [main]

jobs:
  index:
    steps:
      - uses: actions/checkout@v4
      - 

```
