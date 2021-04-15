# Optimized Runge-Kutta Methods with Automatic Step Size Control for Compressible Computational Fluid Dynamics

[![License: MIT](https://img.shields.io/badge/License-MIT-success.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4671927.svg)](https://doi.org/10.5281/zenodo.4671927)

This repository contains coefficients of the optimized Runge-Kutta methods presented in the
[article](https://arxiv.org/abs/2104.06836)
```bibtex
@online{ranocha2021optimized,
  title={Optimized Runge-Kutta Methods with Automatic Step Size Control
         for Compressible Computational Fluid Dynamics},
  author={Ranocha, Hendrik and Dalcin, Lisandro and Parsani, Matteo
          and Ketcheson, David I.},
  year={2021},
  month={04},
  eprint={2104.06836},
  eprinttype={arXiv},
  eprintclass={math.NA}
}
```

If you find these results useful, please cite the article mentioned above. If you
use the coefficients provided here, please **also** cite this repository as
```bibtex
@misc{ranocha2021optimizedCoefficients,
  title={Coefficients of
         Optimized Runge-Kutta Methods with Automatic Step Size Control
         for Compressible Computational Fluid Dynamics},
  author={Ranocha, Hendrik and Dalcin, Lisandro and Parsani, Matteo
          and Ketcheson, David I.},
  year={2021},
  month={04},
  howpublished={\url{https://github.com/ranocha/Optimized-RK-CFD}},
  doi={10.5281/zenodo.4671927}
}
```


## Abstract

We develop error-control based time integration algorithms for 
compressible fluid dynamics (CFD) applications and show that they are 
efficient and robust in both the accuracy-limited and stability-limited regime. 
Focusing on discontinuous spectral element semidiscretizations, we design new 
controllers for existing methods and for some new embedded Runge-Kutta pairs.
We demonstrate the importance of choosing adequate controller parameters and
provide a means to obtain these in practice. We compare a wide range of
error-control-based methods, along with the common approach in which step size
control is based on the Courant-Friedrichs-Lewy (CFL) number. The optimized 
methods give improved performance and naturally adopt a step size close to the
maximum stable CFL number at loose tolerances, while additionally providing
control of the temporal error at tighter tolerances. The numerical examples
include challenging industrial CFD applications.


## Authors

* [Hendrik Ranocha](https://ranocha.de) (University of Münster, Germany)
* Lisandro Dalcin (KAUST, Saudi Arabia)
* Matteo Parsani (KAUST, Saudi Arabia)
* David I. Ketcheson (KAUST, Saudi Arabia)


## Disclaimer

Everything is provided as is and without warranty. Use at your own risk!
