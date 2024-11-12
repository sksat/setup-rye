> [!TIP]
>
> FYI: You might want to use [uv](https://github.com/astral-sh/uv) & [astral-sh/setup-uv](https://github.com/astral-sh/setup-uv)

# setup-rye

This composite action install [rye](https://github.com/mitsuhiko/rye).

## Example workflow
```yaml
name: run pytest
on: pull_request

jobs:
  pytest:
    runs-on: ubuntu-latest
    steps:
      - uses: sksat/setup-rye@v0.8.0
```
