# here-env

Small helper to create and active virtuel environments.

## Usage

```sh
eval $(here-env)
```

This will create and/or activate a venv in `$PWD/.venv` or in
`$GIT_ROOT/.venv`.

You can also create a `here` shell alias:

```sh
alias here='eval $(here-env)'
```
