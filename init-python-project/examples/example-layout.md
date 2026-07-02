# Example Layout

```text
myproject/
├── .gitignore
├── .pre-commit-config.yaml
├── .python-version
├── README.md
├── pyproject.toml
├── setup.cfg
├── uv.lock
└── src/
    └── myproject/
        └── __init__.py
```

`uv.lock` appears after `uv lock` or `uv sync`. `.venv/` is created by `uv sync` but remains ignored by git.
