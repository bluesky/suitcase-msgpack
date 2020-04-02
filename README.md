# suitcase.msgpack

This is a suitcase subpackage for writing a particular file format.

## Installation

```
pip install suitcase-msgpack
```

## Quick Start

```
import suitcase.msgpack
docs = db[-1].documents(fill=True)
suitcase.msgpack.export(docs, 'my_exported_files/', file_prefix='PREFIX-')
```

## Documentation

See the [suitcase documentation](https://nsls-ii.github.io/suitcase).
