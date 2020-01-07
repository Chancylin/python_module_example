lcx: 2020/01/06

This is a quick tutorial example to show how a python package is built.

1. Structure of the package;
2. Necessary files: _setup.py_, _\_init.py__.
3. Specially, one needs to pay attention to the code in_\_init.py__.

```python
from .Gaussiandistribution import Gaussian
```

With this line in _\_init.py__, one can use
```python
from distribution import Gaussian
```
to import Gassian directly. Otherwise,
```python
from distribution..Gaussiandistribution import Gaussian
```

