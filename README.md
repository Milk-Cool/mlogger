# mlogger
A basic logger written in Bash.

## Installation
```bash
curl https://pastebin.com/raw/BNk5vpnB | bash
```
...or, with root rights:
```bash
curl https://pastebin.com/raw/G2pMNYzx | bash
```

## Usage
```bash
LOGPATH=[logpath] mlogger [command]
```
will pipe the output of `command` to `logpath`.
If `$LOGPATH` is unset, it will be set to `$HOME/$1` (home directory -> first argument)
