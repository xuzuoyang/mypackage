# Mypackage

Mypackage is an python package template for convinience of personal project development.

## Inspired by

- https://github.com/bast/somepackage
- https://docs.python-guide.org/writing/structure/
- https://www.makeareadme.com/
- https://keepachangelog.com/en/1.0.0/

## Installation

```bash
pip install mypackage
```

## Usage

```
>>> from mypackage import dict_substract
>>> dict_substract({}, {'a': 11})
{}
>>> dict_substract({'a': 12}, {'a': 11})
{'a': 12}
>>> dict_substract({'a': 11, 'b': 0}, {'a': 11})
{'b': 0}
```

## Support

TBC

## Roadmap

- [ ] add tests.
- [ ] add ci support.
- [ ] add use of pipenv.
- [ ] enrich content in docs.
- [ ] cookiecutter this template.

## Changelog

[Here](docs/CHANGELOG.md)

## License
[MIT](LICENSE)
