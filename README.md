# rafale

Agent harness for defense operations.

## Install

```bash
pip install rafale
```

## Development

```bash
uv sync
uv run pytest
uv run ruff check .
uv build
```

## Releases

Merging a pull request into `main` bumps the minor version and publishes to PyPI.
Publishing uses the `pypi` GitHub environment and a PyPI Trusted Publisher.

## License

[Apache License 2.0](LICENSE).
