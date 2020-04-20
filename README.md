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
suitcase.msgpack.export(docs, 'my_exported_files/')
```
The exported file will have path `my_exported_files/8fe81a89-8103-487a-85d2-23c70af96f16-primary.msgpack`. The default file prefix can be changed with the `file_prefix` keyword argument. See documentation link below.

## Documentation

See the [suitcase documentation](https://nsls-ii.github.io/suitcase).
