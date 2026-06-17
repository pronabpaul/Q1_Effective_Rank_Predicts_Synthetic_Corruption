# Q1. Does effective rank predict performance drop under synthetic corruptions?

**First report in the series:** *Source Representation Geometry Predicts Failure Under Domain Shift in Medical Imaging*  
**Part 1 of 10**

## Overview
This repository contains the first experiment (Q1) in a series of 10 investigations into whether geometric properties of model representations can predict domain shift failure in medical AI. This experiment tests whether **effective rank** predicts performance drop under **synthetic corruptions** (noise, blur, contrast).

## Key Findings
- **H₁ is NOT supported.**
- The correlation was weakly positive (r = 0.198, 95% CI [0.025, 0.368]).
- Effective rank alone explains only ~4% of the variance in corruption robustness.

## Files
- `Q1_Effective_Rank_vs_Synthetic_Corruptions.ipynb` - Complete code for the experiment (Colab).
- `requirements.txt` - Python dependencies.

## How to Run
1. Open the notebook in Google Colab.
2. Set runtime to GPU.
3. Run the cell.
