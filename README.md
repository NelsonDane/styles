# Style Repo

> **'Cause we never go out of style!** - Style (Taylor Swift)

This repository contains a centralized location for style configurations for use across my various projects.

## Current Styles
Add this repository as a git submodule, then extend the relevant style in your project's configuration file.

### Python
- [Ruff](https://github.com/charliermarsh/ruff)

To use, add to `pyproject.toml`:

```toml
[tool.ruff]
extend = ["./styles/ruff.toml"]
```

Used in:
- [Fennel Invest API](https://github.com/NelsonDane/fennel-invest-api)
- [Public Invest API](https://github.com/NelsonDane/public-invest-api)
