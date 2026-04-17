# GNSS Smoothing with DCE - Potsdamer Platz, Berlin


:q
exit()
## Live Interactive Map
**View the map here:** https://prakash023.github.io/GNSS-Smoothing-with-DCE---Potsdamer-Platz/

## Results
- Raw GNSS RMSE: 5.88 m
- DCE Smoothed RMSE: 5.87 m
- Improvement: 0.2%

## Why so little improvement?
Paper got ~50% with UWB+odometry. My data is GNSS only in urban canyon.

## Files
- `error_comparison.png` – Error over time
- `trajectory_comparison.png` – Path comparison
- `weight_function.png` – cDCE weights
- `summary_table.png` – Metrics table
- `index.html` – Interactive map
