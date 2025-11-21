# Float Precision Problems

| Description                 | float64    | float16    | Symbolic Term                     |
|----------------------------|------------|------------|-----------------------------------|
| Small Numbers              | 1.000e-08  | 0.000e+00  | $10^{-8}$                         |
| Big Numbers                | 7.000e+04  | inf        | $70000$                           |
| Long Sum                   | 1.000e+04  | 9.992e+03  | $\sum_{k=1}^{10^{5}} 0.1$         |
| Catastrophic Cancellation  | 1.000e-04  | 0.000e+00  | $1 - (1 - 10^{-4})$               |
