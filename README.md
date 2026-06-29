# Cosmological Data Analysis

10,000 simulated datasets  
512³ grid resolution  
50 smoothing levels per dataset  
Fourier-space processing  

![Key Results](reports/figures/key_results.png)

---

## Analysis Results

![Model Comparison](reports/figures/model_comparison.png)

Output depends on preprocessing method.  
One configuration aligns with reference outputs.  
All other configurations show structured deviations linked to processing choices.

---

![Residual Analysis](reports/figures/residual_analysis.png)

Difference between computed values and reference curves.  
Systematic deviations across parameter ranges.  
Largest differences depend on configuration.

---

## Data Set

- 10,000 datasets  
- 512³ grid  
- periodic boundary conditions  
- Fourier-space generation  
- 50 smoothing steps  
- multiple configurations  

---

## Analytical Workflow

- generate datasets  
- apply Fourier processing  
- smooth signals  
- compute outputs  
- compare results  
- calculate deviations  

---

## Model Comparison

- multiple reference outputs  
- full-range comparison  
- configuration-dependent results  
- structured deviations across parameter space  

---

## Technical Implementation

- C++ implementation  
- batch processing  
- FFT-based computation  
- deterministic runs  
- identical processing steps per dataset  

---

## Repository Structure
