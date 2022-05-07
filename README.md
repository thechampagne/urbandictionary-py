# Urbandic

[![](https://img.shields.io/github/v/tag/thechampagne/urbandictionary-py?label=version)](https://github.com/thechampagne/urbandictionary-py/releases/latest) [![](https://img.shields.io/github/license/thechampagne/urbandictionary-py)](https://github.com/thechampagne/urbandictionary-py/blob/main/LICENSE)

Urban Dictionary API client for **Python**.

### Download
[PyPI](https://pypi.org/project/urbandic/)

```
pip install urbandic
```

### Example

```py
from urbandic import search

for i in search("Python"):
    print(i.definition)
```

### License

Urbandic is released under the [MIT License](https://github.com/thechampagne/urbandictionary-py/blob/main/LICENSE).