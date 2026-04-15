# stretch-sense-glove-research

Research workspace for experimentation and analysis with StretchSense gloves.

## Development setup

This project uses:

- [`uv`](https://docs.astral.sh/uv/) for Python environment and package management
- [`pre-commit`](https://pre-commit.com/) for automated local quality checks

### Quick start

```bash
uv sync
uv run pre-commit install
uv run pre-commit run --all-files
```
