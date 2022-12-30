# any2line

Anything that can be lined up (line hit)
- [ ] _gui
```
/import *T
/rotate *T
/resize *T
/export *T

/add *L
/delete *L
/update *L
```

- [ ] pixels2line - bitwise operations between pixels and lines
```
Line as L
	[ 1 ] * len(T)
Target as T
	[ 0 0 1 0 0 ]	:: T.hit(L)
	[ 1 0 0 0 0 ]	:: T.rotate()
	[ 1 0 0 0 1 ]	:: T.hit(L)
	[ 0 0 0 0 0 ]
	[ 0 0 1 0 0 ]
Output
	[ 0 0 1 0 0 ]
	[ 1 0 1 0 0 ]
	[ 1 1 1 1 1 ]
	[ 0 0 1 0 0 ]
	[ 0 0 1 0 0 ]
```
