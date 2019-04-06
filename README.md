[![Build Status](https://travis-ci.org/RedFT/Hexy.svg?branch=master)](https://travis-ci.org/RedFT/Hexy)

# Hexy, A library for dealing with hexagonal coordinate systems.

A library that makes working with a hexagonal lattice easier. Some of the inspiration for this library comes from [http://www.redblobgames.com/grids/hexagons/](http://www.redblobgames.com/grids/hexagons/).

![Alt text](/Hexy.gif?raw=true "Short Demo")

## Getting Started

### Installing via pip

```bash
pip install hexy
```

### Dependencies

To install the dependencies run:
```bash
pip install -r requirements.txt
```

### Installing

Just clone this repository into your project's root.

## Running the example

We'll use the [HexyExamples](https://github.com/redft/hexyexamples) repo to demonstrate
`hexy`.

```
git clone https://github.com/redft/hexyexamples
cd hexyexamples
pip install -r requirements.txt
python2 example.py
```

The example app just shows off some features of the library. To play around you can:

```
- right click to change the hex selection type. 
- scroll up and down to change the radius of selection when selection type is ring or disk.
- left click to change the starting point of the line when selection type is a line.
```

## Authors

* **Norbu Tsering** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

