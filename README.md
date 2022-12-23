# giant-cli

> Best approach for a fresh install due to docker group permissions requiring logging out or `newgrp` to take effect
```bash
curl -fsSL https://github.com/anthonyra/giant-cli/releases/latest/download/giant-cli | bash -s -- install
```
```bash
curl -fsSL https://github.com/anthonyra/giant-cli/releases/latest/download/giant-cli | bash -s -- setup
```

OR

```bash
curl -fsSL https://github.com/anthonyra/giant-cli/releases/latest/download/giant-cli | bash -s -- setup --install
```
> Installs the Giant CLI during setup. This command will halt installation if current user hasn't been added to the docker group before. Recommend using the install script instead unless docker exists and properly installed on the machine already.

```bash
curl -fsSL https://github.com/anthonyra/giant-cli/releases/latest/download/giant-cli | bash -s -- setup
```
> Doesn't install Giant CLI during setup

```bash
curl -fsSL https://github.com/anthonyra/giant-cli/releases/latest/download/giant-cli | bash -s -- --help
```
> For more commands and options
