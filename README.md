# WeakIV.jl

Post-estimation diagnostics and weak-instrument robust inference for instrumental variables models in Julia.

> [!NOTE]
> WeakIV.jl is under active development.


## Overview

WeakIV.jl provides post-estimation tools for instrumental variables (IV) models, with an emphasis on inference that remains valid under weak identification.

The package separates estimation from inference, allowing users to apply weak-instrument diagnostics, hypothesis tests, and confidence-set procedures to previously estimated models.

The goal is to provide a unified and extensible Julia interface for classical and modern methods in the weak-IV literature following the recomendation of [Lee and Porter (2026)](https://www.aeaweb.org/articles?id=10.1257/jep.20251464) 




## Julia ecosystem

The package is designed to integrate with:

- [Regress.jl](https://github.com/gragusa/Regress.jl) for IV estimation.
- [CovarianceMatrices.jl](https://github.com/gragusa/CovarianceMatrices.jl) for robust covariance estimation.

Potential extensions include integration with local projections and other econometric models estimated using external instruments.




## License

See [LICENSE](LICENSE).
