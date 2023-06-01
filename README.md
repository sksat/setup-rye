# setup-rye

## Example workflow
```yaml
name: run pytest
on: pull_request

jobs:
  pytest:
    runs-on: ubuntu-latest
    steps:
      - uses: sksat/setup-rye@v0.1.0
```
