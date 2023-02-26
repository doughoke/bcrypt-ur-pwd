# bcrypt-ur-pwd
Simple python code to prompt user to create bcrypted password. Literally just took what is in Prometheus documentation...

## Rationale
Was making a simple test to see how to create auth on top of prometheus endpoints... https://prometheus.io/docs/guides/basic-auth/

Became more of a place holder for the script that is provided in the documentation so I do not have to copy pasta.

## Requirements
python 3.9
pip
pipenv

## How to run...

Simply clone the repo

```
git clone https://prometheus.io/docs/guides/basic-auth/
```

Install requirements

```
pipenv install
```

Run the script

```
pipenv run python encrypt-it.py
```

It will prompt you for a string and output encrypted string to stdout

## Troubleshooting

### when I run pipenv run python ecrypt-it.py, I get python cannot be found error?

Try python3 instead of the word python

### I can't seem to get pipenv to run...

Try to install pipenv with pip

```
pip install pipenv
```

## Kudos
Thanks Prometheus Community!

## Contributions
Make an issue if you want.