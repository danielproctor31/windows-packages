# windows-packages

Repository of exported packages using WinGet, Chocolatey and Scoop. Can be used to automate installing software on a new Windows install.

These files were generated by running:

```
winget export winget.json
choco export chocolatey.config
scoop export > scoop.json
```

## Requirements

- [WinGet](https://github.com/microsoft/winget-cli)
- [Chocolatey](https://chocolatey.org/install)
- [Scoop](https://scoop.sh/)

## Usage

### WinGet

`winget import winget.json`

### Chocolatey

**Requires an admin shell.**

`choco install chocolatey.config`


### Scoop

`scoop import scoop.json`