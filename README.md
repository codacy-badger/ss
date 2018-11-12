# Simple shell

A simple shell.
![Coverity](https://scan.coverity.com/projects/17208/badge.svg)

[![asciicast](https://asciinema.org/a/BvThSoa4Q7jW8ymcYkqoZ7vSb.svg)](https://asciinema.org/a/BvThSoa4Q7jW8ymcYkqoZ7vSb)

## Usage:

```
ss: help:

cd - Change directory
		Usage: cd [directory]

set - Set enviromental variable
		Usage: set [variable] [value]

echo - Echo arguments back
		Usage: echo [text] <more text...>

pwd - Path of working directory
		Usage: pwd

exit - Exits shell
		Usage: exit <error code>

routine - Creates a new routine
		Usage:
		~ > routine [name]
		  routine> [code]
		  routine> end

unroutine - Deletes a routine
		Usage: unroutine [name]

help - Display this.  If there's one command that you don't want to forget, it's this one
		Usage: help
```

## How to build

```
$ ./build.sh
$ install ss /path/to/your/bin
```





Inspired by [s](https://github.com/rain-1/s), rc, [es](https://github.com/wryun/es-shell), and the Suckless people