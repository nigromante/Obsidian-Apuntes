[[Radare]]
``` Usage
$ r2 /bin/ls   # open file in read-only

> aaa          # analyse the program (r2 -A)
> afl          # list all functions (try aflt, aflm)
> px 32        # print 32 byte hexdump current block
> s sym.main   # seek to main (using flag name)
> f~foo        # filter flags matching 'foo' (internal |grep)
> iS;is        # list sections and symbols (rabin2 -Ss)
> pdf; agf     # disassembly and ascii-art function graph
> oo+;w hello  # reopen in read-write and write a string
> ?*~...       # interactive filter in all command help
> q            # quit
```