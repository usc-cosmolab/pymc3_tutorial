# PyMC3 Tutorial

The notebook `pymc3_tutorial.ipynb` contains a short PyMC3 tutorial. There we simulate some data using a sine function with amplitude `A` and wave number `k` as an underlying model. Then we add some Gaussian noise on top to emulate a mock observation. Finally using PyMC3 we infer the underlying parameters using MCMC chains.  

In order to run the whole notebook you need the `pymc3` python package for the inference section, as well as `getdist` (or `pygtc`) for the contour plots.

```bash
pip install pymc3
```

```bash
pip install getdist
```

and/or

```bash
pip install pygtc
```

