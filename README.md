# `slitherup`

Update or revert to a specific Slither branch with ease.

## Installing

```sh
curl -L https://0xalpharush.github.io/slitherup/install | bash 
```

## Usage

To install the latest version from **master**:

```sh
slitherup
```

To install a specific **branch** (in this case the `dev` branch's latest commit):

```sh
slitherup --branch dev
```

To install a **fork's main branch** (in this case `0xalpharush/slither`'s main branch):

```sh
slitherup --repo 0xalpharush/slither
```

To install a **specific branch in a fork** (in this case the `feat/read_storage` branch's latest commit in `0xalpharush/slither`):

```sh
slitherup --repo 0xalpharush/slither --branch feat/read_storage
```

---

**Tip**: All flags have a single character shorthand equivalent! You can use `-v` instead of `--version`, etc.

---

## Acknowledgements

This script was derived from [foundryup](https://github.com/gakonst/foundry/blob/master/foundryup/README.md).