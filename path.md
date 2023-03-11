# This file contains some useful snippets that I am using frequently.


## Create temp file name

```python
from os import path
import tempfile


def create_temp_name():
    tmp_dir = tempfile.gettempdir()
    rdn_name = next(tempfile._get_candidate_names())
    return path.join(tmp_dir, rdn_name)
```
