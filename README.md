# GEX
`gex` is a simple bash script for pwn'ing websites with .git repositories available

## Usage
```console
$ ./gex -h
Usage: gex {dump|extract} [OPTIONS]
```
### `dump` switch
```console
$ ./gex dump -h
Usage: gex dump URL DIR
```
```console
$ gex dump http://target.com/.git/ output
```

### `extract` switch
```console
$ ./gex extract -h
Usage: gex extract GIT-DIR DEST-DIR
```

```console
$ ./gex extract /path/to/gitdir/ output
```


# License
All tools are licensed using the MIT license. See [LICENSE.md](LICENSE.md)
