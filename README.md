orbit-pdf [fork]
=========

CLI tool for converting [Orbit](https://github.com/sharu725/online-cv) HTML resume to pdf

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@zsevic/orbit-pdf.svg)](https://npmjs.org/package/orbit-pdf)
[![Downloads/week](https://img.shields.io/npm/dw/@zsevic/orbit-pdf.svg)](https://npmjs.org/package/orbit-pdf)
[![License](https://img.shields.io/npm/l/@zsevic/orbit-pdf.svg)](https://github.com/zsevic/orbit-pdf/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @zsevic/orbit-pdf
$ orbit-pdf COMMAND
running command...
$ orbit-pdf (-v|--version|version)
@zsevic/orbit-pdf/1.0.0 linux-x64 node-v15.10.0
$ orbit-pdf --help [COMMAND]
USAGE
  $ orbit-pdf COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`orbit-pdf convert`](#orbit-pdf-convert)
* [`orbit-pdf help [COMMAND]`](#orbit-pdf-help-command)

## `orbit-pdf convert`

Converts html resume to pdf

```
USAGE
  $ orbit-pdf convert

OPTIONS
  -l, --lastPage=lastPage  last page to print
  -p, --path=path          path for downloaded pdf resume
  -u, --url=url            html resume url

DESCRIPTION
  ...
  Converts html resume to pdf and downloads it
```

## `orbit-pdf help [COMMAND]`

display help for orbit-pdf

```
USAGE
  $ orbit-pdf help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_
<!-- commandsstop -->
