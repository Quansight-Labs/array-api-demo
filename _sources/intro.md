# Array Libraries Interoperability

This is a small sample tutorial to give you a feel for how the future of array consumer and provider libraries may look after the adoption of [Array API](https://data-apis.org/array-api/latest/).


No more fiddling around with docs when switching an implementation from one array framework
to another. Simply change the import and switch your array/tensor implementation library:

```
import torch as xp
# or
import numpy.array_api as xp


a = xp.arange(3)
b = xp.ones(3)

c = a + b
```

Check out the Array API Prototype Demo page bundled with this book to see the real use case with a library like [SciPy](https://github.com/scipy/scipy).

:::{note}
Python Array API is currently under development and the demo here is only a prototype.
:::