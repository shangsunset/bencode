# bencode

decode torrent file into a dict

```python

import bencode as b

exp = 'd3:cow3:moo4:spam4:eggse'

d = b.decode(exp) # d =  {'cow': 'moo', 'spam': 'eggs'}

```
