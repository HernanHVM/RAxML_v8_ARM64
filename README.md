# RAxML_v8_ARM64
A sanitized Makefile for Apple M chips under ARM64 architecture, since the .mac x86 Makefiles produce binaries that crash .

## Follow these instructions from the original RAxML 8.2.12 github repository with a tiny modification
https://github.com/stamatak/standard-RAxML

type:

```
make -f Makefile.PTHREADS.arm64s

rm *.o
```


