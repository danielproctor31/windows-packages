# windows-packages

Repository of exported packages using Chocolatey and Scoop. Can be used to automate installing software on a new Windows install.

## Requirements

- [Chocolatey](https://chocolatey.org/install)
- [Scoop](https://scoop.sh/)

## Usage

### Scoop

`scoop import .\scoop.json`

### Chocolatey

**Requires an admin shell.**

`choco import .\chocolatey.config`