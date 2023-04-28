# Installation

A few different installation options are offered for `igir`.

## Via Node.js

[![npm: version](https://img.shields.io/npm/v/igir?color=%23cc3534&label=version&logo=npm&logoColor=white)](https://www.npmjs.com/package/igir)
[![Node.js](https://img.shields.io/node/v/igir?label=Node.js&logo=node.js&logoColor=white)](https://nodejs.org/en/download/)

The best way to ensure that you are always running the most up-to-date version of `igir` is to run it via [`npx`](https://docs.npmjs.com/cli/v9/commands/npx) which comes installed with Node.js:

```shell
npx igir@latest [commands..] [options]
```

for example:

```shell
npx igir@latest copy extract --dat *.dat --input ROMs/ --output ROMs-Sorted/ --dir-dat-name
```

[![asciicast](https://asciinema.org/a/hjMOlN3DwSgo9NGHzPtncOoq9.svg)](https://asciinema.org/a/hjMOlN3DwSgo9NGHzPtncOoq9)

## Via downloaded executable

[![GitHub: release](https://img.shields.io/github/v/release/emmercm/igir?color=%236e5494&logo=github&logoColor=white)](https://github.com/emmercm/igir/releases/latest)

If you don't want to download Node.js, you can download executables for different OSes from the [GitHub releases](https://github.com/emmercm/igir/releases) page.

## Via Docker

If none of the above options work for you, [Docker](https://www.docker.com/) may be an option. You will need to mount your input and output directories as volumes, which will significantly reduce your file read and write speeds.

```shell
docker run --interactive --tty \
  --volume "$PWD:/pwd" \
  --workdir "/pwd" \
  node:lts \
  npx igir@latest copy zip --dat "*.dat" --input ROMs/ --output ROMs-Sorted/ --dir-dat-name
```

!!! warning

    Make sure to quote all of your [file globs](file-scanning.md)!

[![asciicast](https://asciinema.org/a/5OAVbSXXoosTr0WyBvjQGBqRp.svg)](https://asciinema.org/a/5OAVbSXXoosTr0WyBvjQGBqRp)