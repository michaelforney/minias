# minias

A mini assembler for x86_64, written for fun and learning.

Goals:

- A simple, tiny, fast implementation (in that order).
- Assemble the output of [cproc](https://github.com/michaelforney/cproc)/[qbe](https://c9x.me/compile/) and [chibicc](https://github.com/rui314/chibicc).
- Relocatable elf output.

Non Goals:

- Assemble every assembly instruction.
- Assemble other architectures.
- Work as a library.

# Building

```
redo minias
```

or 

```
leg asm.peg > asm.peg.inc
cc -O2 *.c -o minias
```

# Resources

- [elf spec](https://refspecs.linuxfoundation.org/elf/elf.pdf)
- [goas](https://github.com/DQNEO/goas)
- [neatas](https://repo.or.cz/neatas.git)
