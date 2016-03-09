# python-structio
Convenient, readable, struct-based stream I/O

```python
import structio

s = structio.StructIO('\xad\xde\xef\xbe')
s.peek_uint16()  # "dead"
```
