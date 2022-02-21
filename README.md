# pre-commit-pycodestyle-hook

Mirror of the pycodestyle (former pep8) package for pre-commit

For pre-commit: see https://github.com/pre-commit/pre-commit

For pycodestyle: see https://github.com/PyCQA/pycodestyle

### Using pycodestyle with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo:  https://github.com/SuperSolik/pre-commit-pycodestyle-hook
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: pep8
```

### Included `args`

Note that [this repository] sets `args: ["--show-pep8", "--statistics"]` flags.
