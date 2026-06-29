# Cosmological Data Analysis

10,000 simulated datasets  
512³ grid resolution  
Fourier-based generation  
50 smoothing steps per run  

---

![Key Results](reports/figures/key_results.png)

One configuration produces stable alignment with reference outputs.  
All other configurations deviate consistently.

No randomness observed in deviation structure.

---

## Output comparison

![Model Comparison](reports/figures/model_comparison.png)

Same datasets, different preprocessing paths.

Output shifts depending on configuration choice.

Pattern is stable across full parameter range.

---

## Residuals

![Residual Analysis](reports/figures/residual_analysis.png)

Difference to reference output.

Not noise.

Deviations repeat across runs.

Some parameter regions more sensitive than others.

---

## Data

- 10,000 datasets  
- 512³ grid  
- periodic boundary conditions  
- Fourier-space generation  
- repeated runs on identical inputs  
- configuration changes only  

Raw structure identical across all runs.

---

## Processing

- dataset generation in batch execution  
- Fourier transform applied per dataset  
- smoothing across multiple scales  
- identical pipeline reused across runs  
- only configuration varies  
- deterministic computation

---

## Comparison

- multiple reference outputs  
- full-range evaluation  
- configuration-dependent results  
- deviation patterns repeat consistently  

---

## Pipeline

C++ batch execution  
FFT-based processing  
fixed computation steps  
parameter sweep only  
no structural changes between runs  

---

## Notes

Synthetic data only  
No external measurements  
Restricted configuration space  
Results depend entirely on preprocessing choice  

---

## Source

Bachelor Thesis (University of Heidelberg, 2020)  
Colloquium presentation (2020)
