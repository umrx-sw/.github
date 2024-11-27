# umrx-sw

We redefine visualizing digital sensor data.

## [`umrx-app-v3`](https://github.com/umrx-sw/umrx-v3-py)

The [`umrx-app-v3`](https://github.com/umrx-sw/umrx-v3-py) 
`python-3` library communicates with Bosch Sensortec evaluation boards:
Application Board
[3.1](https://www.bosch-sensortec.com/software-tools/tools/application-board-3-1/) and 
[3.0](https://www.bosch-sensortec.com/software-tools/tools/application-board-3-0/) 
running [COINES](https://github.com/boschsensortec/COINES_SDK) firmware.

The library is designed to save your time and effort while interfacing with sensors 
on your BST evaluation boards.

### 🌟 Key Features

* **pure python**: no need for C-library wrapper 
  (as in [coinespy](https://github.com/boschsensortec/COINES_SDK/tree/main/coines-api/pc/python/coinespy)), 
  all code is written in `python3`, with only 
  [`pyserial`](https://pypi.org/project/pyserial/) and 
  [`pyusb`](https://pypi.org/project/pyusb/) dependencies;
* **user-friendly API**: clear, pythonic methods for sending commands and receiving sensor data;
* **support for 
  [3.1](https://www.bosch-sensortec.com/software-tools/tools/application-board-3-1/) and 
  [3.0](https://www.bosch-sensortec.com/software-tools/tools/application-board-3-0/)
  hardware**: both evaluation boards are supported and tested;
* **extensibility**: the project can be easily extended to work with new shuttle boards;
* **cross-platform**: works on Linux, Mac, and Windows.

### 🛠️ Installation and Usage
Install and try it out [`umrx-app-v3`](https://github.com/umrx-sw/umrx-v3-py) via pip:

```bash
pip install umrx-app-v3
```

Take a look at the available [examples](https://github.com/umrx-sw/umrx-v3-py/tree/main/examples).
