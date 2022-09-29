# poetry-in-subfolder

Setting up a poetry environment in a subfolder

## Usage

Use like

```yaml
...
jobs:
  steps:
    ...
    - name: Setup Poetry Poetry
      uses: djohn156/poetry-in-subfolder@v1
      with:
        path: path/to/python/project
    ...
```
