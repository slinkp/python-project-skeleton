# Skeleton for my standard python project setup

This installs and configures my current preferred set of development tools, and
nothing else.

To use:

- Copy all these files into a new repo
- Don't forget `.envrc` to set up my direnv
- May want to add `.envrc` to gitignore if going to add api keys etc
- Replace this README with something useful :)

Then install and freeze packages:

```console

pip install -r requirements-minimal.txt
pip freeze -r requirements-minimal.txt > requirements.txt

```
