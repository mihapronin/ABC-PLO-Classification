# ABC segmentation with PWLF (Pareto curve, variable K)

This repository contains a reproducible notebook for **ABC-like segmentation** with an arbitrary number of classes **K**.
Instead of fixed thresholds (e.g., 80/95/100), we segment based on the **shape of the cumulative Pareto curve** by fitting a
**piecewise linear function (PWLF)** and selecting **K via an elbow criterion**.

## Notebook
- View (static): https://nbviewer.org/github/mihapronin/ABC-PLO-Classification/blob/main/ABC_PLO_PWLF_UCI.ipynb
- Run (interactive): https://colab.research.google.com/github/mihapronin/ABC-PLO-Classification/blob/main/ABC_PLO_PWLF_UCI.ipynb

## What you get (outputs used in the article)
- Pareto curve + PWLF segmentation (visual segment boundaries)
- SSE vs K plot (elbow selection)
- Final class summary table (SKU share, value share, density vs average)
