schoolsyst
==========

A CLI Frontend for the schoolsyst API. See git.schoolsyst.com/backend

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/schoolsyst.svg)](https://npmjs.org/package/schoolsyst)
[![Downloads/week](https://img.shields.io/npm/dw/schoolsyst.svg)](https://npmjs.org/package/schoolsyst)
[![License](https://img.shields.io/npm/l/schoolsyst.svg)](https://github.com/schoolsyst/cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g schoolsyst
$ schoolsyst COMMAND
running command...
$ schoolsyst (-v|--version|version)
schoolsyst/0.0.1 linux-x64 node-v13.8.0
$ schoolsyst --help [COMMAND]
USAGE
  $ schoolsyst COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`schoolsyst hello [FILE]`](#schoolsyst-hello-file)
* [`schoolsyst help [COMMAND]`](#schoolsyst-help-command)

## `schoolsyst hello [FILE]`

describe the command here

```
USAGE
  $ schoolsyst hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ schoolsyst hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/schoolsyst/cli/blob/v0.0.1/src/commands/hello.ts)_

## `schoolsyst help [COMMAND]`

display help for schoolsyst

```
USAGE
  $ schoolsyst help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.3/src/commands/help.ts)_
<!-- commandsstop -->