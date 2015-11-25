# wxytest
```python
#!/usr/bin/env python
import sys
a=input()
print(a)
```

```flow
s=>start:Start
op=>operation:op
cond=>condition:Yes OR No?
e=>end:End
s->op
op->cond
cond(yes)->e
cond(no)->op
```
