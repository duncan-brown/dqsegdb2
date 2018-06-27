DQSEGDB2 is a simplified Python implementation of the DQSEGDB API as defined in
LIGO-T1300625.

This package only provides a query interface for `GET` requests, any users
wishing to make `POST` requests should refer to the official `dqsegdb` Python
client available from https://github.com/ligovirgo/dqsegdb/.

# Basic Usage

```python
>>> from dqsegdb2.query import query_segments
>>> print(query_segments('G1:GEO-SCIENCE:1', 1000000000, 1000001000))
```