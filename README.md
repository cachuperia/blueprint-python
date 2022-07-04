# blueprint-python
![checks][checks] ![release][release]
## Table of contents
* [About](#about)
* [Development](#development)
  * [Prerequisites](#prerequisites)
  * [Setup local environment](#setup-local-environment)
  * [Contribute](#contribute)

## About

GitHub template for Python package blueprint.

## Development

Release can be triggered by commit with `feat` or `fix` prefix. Check

### Prerequisites

Tools to install: [git][g], [pre-commit][pk], [poetry][p].

You can use [this][a] playbook for automated tools installation(Ubuntu only).

### Setup local environment

```shell
git clone git@github.com:agblox/blueprint-python.git
cd blueprint-python
make init
direnv allow
```
Run `make` for list all available targets.

### Contribute

Use [Conventional Commits][cc] message style.

[a]: https://github.com/IaroslavR/ansible-role-server-bootstrap
[cc]: https://www.conventionalcommits.org/en/v1.0.0/
[g]: https://www.atlassian.com/git/tutorials/install-git
[p]: https://python-poetry.org/docs/#installation
[pk]: https://pre-commit.com/#install

[checks]: https://github.com/agblox/blueprint-python/actions/workflows/checks.yml/badge.svg
[release]: https://github.com/agblox/blueprint-python/actions/workflows/release.yml/badge.svg

[wch]: .github/workflows/checks.yml
[wr]: .github/workflows/release.yml
