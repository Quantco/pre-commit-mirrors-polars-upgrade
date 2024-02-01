# polars-upgrade pre-commit hook

pre-commit hook of polars-upgrade with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For polars-upgrade: see [here](https://github.com/MarcoGorelli/polars-upgrade)

## Using polars-upgrade with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-polars-upgrade
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: polars-upgrade-conda
```
