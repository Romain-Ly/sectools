## exploit function by LD_PRELOAD trick

```
gcc -m32 ld_preload.c -o /tmp/lib.so -shared -fPIC
export LD_PRELOAD=/tmp/lib.so
```
