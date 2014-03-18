= asched - asynchronous scheduler for Python 3.4

This reimplements the standard sched module. Its behavior differs
from the standard by gracefully handling overlapping event time frames,
by utilizing the asyncio module as a backend.

This is (and will only ever be) support by version 3.4 or later of Python.

STATUS

It is currently an incomplete work in progress.

AUTHOR

Aaron Maxwell
amax AT redsymbol DOT net

LICENSE

This software is in the public domain.
