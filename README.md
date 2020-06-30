# DVC Getting Started

This repo is a step by step independent walkthrough of the [DVC Get Started](https://dvc.org/doc/start/) guide.

### Gotchas

#### Pipfiles
I'm using `pipenv`, so all of my `dvc run` commands have `pipenv run python ...` 
in them instead of just python invocations. This might break your workflow.

To install the dependencies initially, run:

```bash
pip install pipenv # if it's not installed yet
pipenv --python 3.7
pipenv install -r ./src/requirements.txt
```
