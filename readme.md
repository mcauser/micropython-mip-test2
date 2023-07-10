# MicroPython MIP test 2

One in a series of example repos to test various mpremote mip installation patterns.

#### Install

```
$ mpremote mip install github:mcauser/micropython-mip-test2

Install github:mcauser/micropython-mip-test2
Installing github:mcauser/micropython-mip-test2/package.json to /lib
Installing: /lib/test2a.py
Installing: /lib/test2b.py
Done
```

GitHub         | Device
:--------------|:--------------
/src/test2a.py | /lib/test2a.py
/src/test2b.py | /lib/test2b.py

```
$ mpremote repl

>>> import test2a
test2a
>>> import test2b
test2b
```
