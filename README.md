# Python wrapper for [DBoW3](https://github.com/rmsalinas/DBow3)

Originally used to implement ORBSLAM2 with Python. 

This repo will consider supporting more general application scenarios.


## Prerequisites

* A compiler with C++11 support
* CMake >= 2.8.12
* Numpy
* OpenCV 4 (not opencv-python)


## Installation

**Note: DO NOT use:** `pip install DBoW3Py`

1. Clone this repository
2. Create `/build` folders in both root and `/Dow3` folders
3. Enter each `/build` folder and compile and build the package
```
cmake ..
make
sudo make install
```
4. Go back to the root directory (i.e., `/Python-DBoW3`), run
```
pip install .
```

## Usage

```python
import DBoW3Py as dbow
```

more examples are coming 

## License

PyDBoW3 is provided under a BSD-style license that can be found in the LICENSE
file. By using, distributing, or contributing to this project, you agree to the
terms and conditions of this license.
