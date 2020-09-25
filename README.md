* Commands must be on a single line.
* Arguments must be separated by whitespace.
* No quoting arguments or escaping whitespace.
* No piping or redirection.
* Only builtins are: `cd`, `help`, `exit`.

Running
-------

Use `gcc -o lsh src/main.c` to compile, and then `./lsh` to run. If you would
like to use the standard-library based implementation of `lsh_read_line()`, then
you can do: `gcc -DLSH_USE_STD_GETLINE -o lsh src/main.c`.


