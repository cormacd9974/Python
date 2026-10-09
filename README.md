# Python

My work through a self-directed Python course, moving from JavaScript to idiomatic Python: core language, testing, data and ML tooling, FastAPI and async.

## Progress

| # | Module | Status |
| --- | --- | --- |
| 1 | [Setup and tooling](modules/01-setup) | Not started |
| 2 | [Core syntax for JS developers](modules/02-core-syntax) | Not started |
| 3 | [Built-in data structures](modules/03-data-structures) | Not started |
| 4 | [Strings, slicing and formatting](modules/04-strings) | Not started |
| 5 | [Pythonic idioms](modules/05-idioms) | Not started |
| 6 | [Functions, closures and decorators](modules/06-functions) | Not started |
| 7 | [Modules, packages and project structure](modules/07-packages) | Not started |
| 8 | [Errors, files and context managers](modules/08-errors-files) | Not started |
| 9 | [Object-oriented Python](modules/09-oop) | Not started |
| 10 | [Iterators and generators](modules/10-generators) | Not started |
| 11 | [Type hints and testing](modules/11-typing-testing) | Not started |
| 12 | [Standard library tour](modules/12-stdlib) | Not started |
| 13 | [NumPy, pandas and matplotlib](modules/13-data-ml) | Not started |
| 14 | [Web APIs with FastAPI](modules/14-fastapi) | Not started |
| 15 | [Async Python](modules/15-async) | Not started |
| - | [Capstone](capstone) | Not started |

## Setup

```bash
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Tooling

- `ruff check . && ruff format .`
- `mypy .`
- `pytest -v`
