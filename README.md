# opendata.fit ecosystem nix flakes

## frontend flake

Usage in an ```.envrc```:

```
use flake "github:opendatafit/flakes?dir=frontend" --no-write-lock-file
```

## backend flake

## Development environment

Project contains a ```.envrc``` loaded by ```direnv``` which loads the Nix flake defined in ```flake.nix```.

First have to allow ```direnv```:
```
direnv allow
```


### README.md

Start github markdown viewer:

```
grip
```

Then navigate in-browser to: ```localhost:6419```
