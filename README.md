# arrive

Switch location related configuraion

## Install

1. copy `bin/arrive` to user path, e.g. `/usr/local/bin`
2. copy `location.d` to install diretory, e.g. `/usr/local/etc`

## Syntax

```
arrive [location] 
```

## Usage

All location related configuration will be located in `~/.location`.

### Reference in scripts

Add the following line to your `.zshrc`

```bash
...
source $HOME/.location/.zshrc
...
```

### Link to scripts

```bash
~$ ln -s .location/.npmrc .npmrc
```
