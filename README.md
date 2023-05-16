# 42sh

This is our final branch project at epitech, an UNIX shell with several POSIX builtins.

## TO DO

Add `make test` for linux

## Usage

```
usage: ./42sh
```

### Linux/OSX :

```
make re
./42sh
```

FEATURES
---

- [x] Builtins
	- [x] cd [-L|-P] [directory]
	- [x] echo [string...]
	- [x] exit [n]
	- [x] env [-i] [name=value]... [utility [argument...]]
	- [x] setenv
	- [x] unsetenv
	- [x] unset [-fv] name...

- [x] Execution
	- [x] Execution of commands with their parameters and PATH management.
	- [x] Management of errors and the return value of commands.
	- [x] The following redirects: ">", "<<", ">>", "<".
	- [x] Pipes “|”.
	- [x] The logical operators "&&" and "||".
	- [x] Back quotes "'".
	- [x] The ";" separator.

- [x] Signals
	- [x] ctrl+D
	- [x] ctrl+C

- [x] Bonuses
	- [x] The "<<" heredoc.
	- [x] Colours.
	- [x] Variables.
	- [x] Aliases.
	- [x] Wich/Where.
    - [x] History.

- [x] Structure
	- [x] init
	- [x] edit input
	- [x] break input
	- [x] parse input
	- [x] word expansion
	- [x] redirect
	- [x] execution
	- [x] wait
