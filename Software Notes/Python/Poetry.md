# Poetry
#python #packaging

Poetry is a [[Package Manager]] tool that helps you "declare, manage and install dependencies of Python project, ensuring you have the right stack everywhere."

complete documentation: https://python-poetry.org/docs/

## Installation
#linux

```bash
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python

source $HOME/.poetry/env
```

## Setup
`poetry init` is a command that will set up an existing repository with the required files, to create or update a `pyproject.toml` file.

```bash
poetry init
```

## Using Poetry

```bash
poetry shell

poetry install
```

```bash
poetry add *package*
```

## Updating Dependencies
```bash
poetry update
```

## Publishing Package

```bash
poetry build

poetry publish
```
