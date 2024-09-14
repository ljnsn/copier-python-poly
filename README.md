# copier-poly-python

[![Copier](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-grayscale-inverted-border-orange.json)](https://github.com/copier-org/copier)

A [`copier`](https://copier.readthedocs.io/) template that supports [`polylith`](https://davidvujic.github.io/python-polylith-docs/) architecture and multiple package managers.

## Features

- Package managers: `uv`, `pdm`, and `poetry`, all with dedicated configuration.
- Project structures: `poly`, `simple`, and `src`.
- Linting & testing: `ruff`, `mypy`, `coverage`, `pytest`
- Tasks: `invoke`
- Release management: `commitizen`, `cz-conventional-gitmoji`
- CI/CD: `pre-commit`, GitLab, GitHub, or CircleCI pipelines (tbd)
- Logging: `loguru`
- Database: `sqlalchemy`, `advanced-alchemy`, `alembic`
