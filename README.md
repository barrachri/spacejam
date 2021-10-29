# Space Jam Inc

## About this app

You are part of the team that explores Mars by sending remotely controlled vehicles to the surface of
the planet.

Write an idiomatic piece of software that translates the commands sent from earth to
actions executed by the rover yielding a final state..

When the rover touches down on Mars, it is initialised with its current coordinates and the direction
it is facing. These could be any coordinates, supplied as arguments ​ (x, y, direction)​ e.g. ​ (4,
2, EAST)​ .

## Requirements

The setup for this project described here requires a
Python 3.8 (or above) installation.

It uses `poetry` for dependency management and installation.

You can install `poetry` with

```bash
pip install poetry
```

### Installation

I recommend you to create a Python environment with

```
python -m venv .venv
```

and then run:

```bash
poetry install --no-dev
```

### Development

To work on this project you will need to install all development dependencies.
To do that you can run:

```bash
poetry install
```

#### Code quality

We run a set of code quality checks: `isort`, `mypy` and `flake8`, you can them as follow:

```bash
# Black code
poetry run black --check src

# Check imports order
poetry run isort -c src

# Flake8 code
poetry run flake8 src
```

#### Test

The tests alone can be executed with `pytest`. To run them:

```bash
poetry run pytest src
```
