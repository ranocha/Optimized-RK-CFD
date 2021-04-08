# Optimized Low-Storage Runge-Kutta Methods with Automatic Step Size Control for Spectral Element Methods Applied to Compressible Computational Fluid Dynamics

[![License: MIT](https://img.shields.io/badge/License-MIT-success.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4671927.svg)](https://doi.org/10.5281/zenodo.4671927)

This repository contains coefficients of the optimized Runge-Kutta methods presented in the
[article](https://arxiv.org/abs/TODO)
```bibtex
@online{ranocha2021optimized,
  title={Optimized Low-Storage Runge-Kutta Methods with Automatic
         Step Size Control for Spectral Element Methods Applied to
         Compressible Computational Fluid Dynamics},
  author={Ranocha, Hendrik and Dalcin, Lisandro and Parsani, Matteo
          and Ketcheson, David I.},
  year={2021},
  month={04},
  eprint={TODO},
  eprinttype={arXiv},
  eprintclass={math.NA}
}
```

If you find these results useful, please cite the article mentioned above. If you
use the coefficients provided here, please **also** cite this repository as
```bibtex
@misc{ranocha2021optimizedCoefficients,
  title={Coefficients of
         Optimized Low-Storage Runge-Kutta Methods with Automatic
         Step Size Control for Spectral Element Methods Applied to
         Compressible Computational Fluid Dynamics},
  author={Ranocha, Hendrik and Dalcin, Lisandro and Parsani, Matteo
          and Ketcheson, David I.},
  year={2021},
  month={04},
  howpublished={\url{https://github.com/ranocha/Optimized-RK-CFD}},
  doi={10.5281/zenodo.4671927}
}
```


## Abstract

We discuss and compare adaptive step size control based on CFL numbers and
error estimates for discontinuous spectral element semidiscretizations of
conservation laws and related problems in computational fluid dynamics (CFD).
We demonstrate the importance of choosing adequate controller
parameters and provide a means to obtain these in practice.
We develop optimized explicit low-storage Runge-Kutta methods with embedded error
estimators for CFD, combined with good step size controllers.
The performance of these new methods is demonstrated in several numerical
experiments with increasing physical complexity.


## Authors

* [Hendrik Ranocha](https://ranocha.de) (University of Münster, Germany)
* Lisandro Dalcin (KAUST, Saudi Arabia)
* Matteo Parsani (KAUST, Saudi Arabia)
* David I. Ketcheson (KAUST, Saudi Arabia)


## Disclaimer

Everything is provided as is and without warranty. Use at your own risk!
