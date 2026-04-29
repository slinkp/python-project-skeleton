# Skeleton for my standard python project setup

This installs and configures my current preferred set of development tools, and
nothing else.

To use:

- Copy all these files into a new empty repo
- Don't forget `.envrc` to set up my direnv
- May want to add `.envrc` to gitignore if going to add api keys etc
- Replace this README with something useful :)

Bootstrap the direnv:

```console
direnv allow
# Entering and leaving a direnv directory causes it to apply the config.
cd ..
cd -
```

Check the right python is active by running `which python`.
It should show a binary in `./direnv/python-3*/bin`
relative to the current directory.

Then install and freeze packages:

```console
pip install -r requirements-minimal.txt
pip freeze -r requirements-minimal.txt > requirements.txt
```
