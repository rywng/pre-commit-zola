<!-- vim: set tw=80: -->

# pre-commit-zola

This is my [pre-commit.com](https://pre-commit.com/index.html) hooks
for developing zola website.

## Usage

Add the following to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/rywng/pre-commit-zola
  hooks:
    - id: zola-check
  # - id: ...
```

Follow the [Official documentation](https://pre-commit.com/index.html#plugins)
for more information.
