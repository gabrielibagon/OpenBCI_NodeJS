# OpenBCI Node SDK to Python

## About

This code provides an example of how to stream OpenBCI data through the [lab streaming layer](https://github.com/sccn/labstreaminglayer) using the NodeJS SDK.

Follow the steps in this README to start streaming. The code is ready to run as-is, but can be modified and extended to customize how you are sending your data. This is designed to be used with the ***OpenBCI Cyton*** (for Ganglion support, see [here](https://github.com/OpenBCI/OpenBCI_NodeJS_Ganglion/tree/master/examples/labstreaminglayer)

## Prerequisites

* [Python](https://www.python.org/downloads/)
* [ZeroMQ](http://zeromq.org/bindings:python)

  ```py
  pip install pyzmq
  ```
* [Node.js LTS](https://nodejs.org/en/)
* [Lab Streaming Layer](https://github.com/sccn/labstreaminglayer)

  ```py
   pip install pylsl
  ```


## Installation
For Python do:
```bash
python setup.py install
```
For Node:
```bash
npm install
```

## Running
```
npm start
```
For running just the node, for example if you were running the python in a separate ide and debugging, it's useful.
```python
npm run start-node
```

## Contributing
Please PR if you have code to contribute!
