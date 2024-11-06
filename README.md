Q6: As shown in the table below, we have conducted comparative experiments with the DMVG method on CUB and Fashion. Our method achieves better clustering results than DMVG at different missing rates. In the next versions, we will include comparative results across all datasets.
| Dataset | Missing Rates | ACC (0.1) | NMI (0.1) | ARI (0.1) | ACC (0.3) | NMI (0.3) | ARI (0.3) | ACC (0.5) | NMI (0.5) | ARI (0.5) | ACC (0.7) | NMI (0.7) | ARI (0.7) |
|---------|---------------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| CUB     | DMVG         | 67.26     | 63.23     | 53.85     | 64.86     | 62.89     | 51.36     | 62.93     | 58.68     | 49.36     | 56.26     | 57.95     | 43.92     |
|         | DCG (Ours)   | **82.23** | **77.70** | **69.21** | **77.17** | **71.35** | **59.85** | **75.50** | **72.21** | **59.12** | **74.67** | **70.19** | **56.41** |
| Fashion | DMVG         | 89.56     | 86.28     | 85.53     | 87.26     | 83.68     | 77.85     | 83.63     | 76.58     | 73.23     | 75.88     | 72.56     | 68.36     |
|         | DCG (Ours)   | **95.83** | **91.29** | **91.19** | **93.13** | **86.99** | **86.00** | **90.04** | **82.25** | **79.99** | **85.76** | **76.42** | **72.79** |
