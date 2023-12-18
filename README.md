polars-upgrade(-conda) mirror
=============================

Mirror of polars-upgrade for pre-commit with conda as a language.

For pre-commit: see https://github.com/pre-commit/pre-commit
For polars-upgrade: see https://github.com/MarcoGorelli/polars-upgrade

### Using polars-upgrade with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-polars-upgrade
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: polars-upgrade-conda
```

