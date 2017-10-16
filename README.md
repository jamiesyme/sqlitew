# SQLite Composer

## Setup

On Linux, make sure you have:

- curl
- build-essentials (gcc, make, etc)
- python2

On Mac, make sure have:

- brew
- Xcode (make sure you've started it at least once)

On Windows, make sure have:

TODO

Once you've installed those tools, run:

```bash
./control.sh setup
```

**Note:** you may be asked to enter your password to install the packages.

Once the setup completes successfully, restart your shell.

## Building

To build:

```bash
./control.sh build
```

To package:

```bash
./control.sh package
```

The packaged app can be found in `build/`.

## Issues

- Linux: the directory "~/.sqlitecomposer" is created automatically when running the program. This seems to be related to the crash reporter being disabled.
