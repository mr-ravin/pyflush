# pyflush
This repository contains python code to remove content of a directory, or file in a safer manner. After running pyflush, it became much safer to delete the file manually/programmatically.

#### Developer: [Ravin Kumar](http://mr-ravin.github.io)

### Steps to use pyflush

- Removing a file

```python
import pyflush
pyflush.flushfile("filename.txt")
```

- Removing a directory

```python
import pyflush
pyflush.flushdir("directoryname")
```

#### Installation using PyPi

```
pip3 install pyflush
```

##### Note: This work can be used freely after providing citation and/or deserved credits to this work. Please use it at your own risk !!!
