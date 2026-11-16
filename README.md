# greet-community

A friendly greeting package

## Install

Use Python 3.11 or newer in an activated virtual environment.

```bash
python -m pip install -e .
```

## Use

Call `greet(name)` to greet a trimmed name; blank names become `world`.
`python -c "from greet_community import greet; print(greet('Hee'))"`
Expected output: `Hello, Hee!`
