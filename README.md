<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [DeepAI](#deepai)
    - [Version](#version)
    - [Tutorial](#tutorial)
    - [Notice](#notice)
    - [Install](#install)
    - [Circuit](#circuit)
    - [Method Chain](#method-chain)
    - [Document](#document)
    - [Contributors](#contributors)
    - [Disclaimer](#disclaimer)
- [DeepAI](#deepai-1)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# DeepAI

Quantum Computing SDK

### Version

[![Version](https://badge.fury.io/py/deepai.svg)](https://badge.fury.io/py/deepai)

### Tutorial

https://github.com/DeepAI/DeepAI-tutorials

### Notice

The back end has been changed to tensor network. The previous backend environment can still be used with .run(backend="numpy").

### Install

```
git clone https://github.com/DeepAI/DeepAI
cd DeepAI
pip3 install -e .
```

or

```
pip3 install deepai
```

### Circuit

```python
from deepai import QAOA, QML, QNN
```

### Method Chain

```python
Circuit().h[0].x[0].z[0]

c = Circuit().h[0]
c.x[0].z[0]
```

### Document


### Contributors

[Contributors](https://github.com/deep-recommend)

### Disclaimer

Copyright 2022 The DeepRecommend Developers.

# DeepAI
