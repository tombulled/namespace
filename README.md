# namespace
Simple namespaces

## Usage
```python
import namespace

functions = namespace()

@functions
def foo(): pass

@functions
def bar(): pass
```

```python
>>> functions
Namespace(bar=<function bar at 0x7f0ceaec3c10>, foo=<function foo at 0x7f0ceb6391f0>)
>>>
>>> functions.foo
<function foo at 0x7fd5d249d1f0>
```
