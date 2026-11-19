# duck

A minimal hello-world project in the [Duckling](https://duckling.pl/) programming language.

## Requirements

Duckling v0.3 toolchain (`duck`, `duckc`). Download the Linux release from
<https://duckling.pl/en/downloads/>, unpack it and run `./install.py`.

## Usage

```sh
duck run      # build and run
duck build    # build only; binary goes to .duck_build/dev/duck
```

Expected output:

```
Hello, world!
```

## Layout

- `quackconfig.yaml` — package manifest (name, version)
- `src/src.dk` — program entry point (`main`)

## Documentation

<https://docs.duckling.pl/>
