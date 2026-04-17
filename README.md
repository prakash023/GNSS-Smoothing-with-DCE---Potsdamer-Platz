# GNSS Smoothing with DCE - Potsdamer Platz, Berlin

Implementation of Dynamic Covariance Estimation (DCE) from Pfeifer et al. 2017 on GNSS data.

## Results
- Raw GNSS RMSE: 5.88 m
- DCE Smoothed RMSE: 5.87 m
- Improvement: 0.2%

## Why so little improvement?
The paper got ~50% improvement but with:
- UWB ranging sensors + wheel odometry
- Indoor lab with controlled obstacles

My setup:
- GNSS only (no odometry)
- Urban canyon at Potsdamer Platz
- Systematic errors, not random outliers

## Files
- `error_comparison.png` – Error over time
- `trajectory_comparison.png` – Path comparison
- `weight_function.png` – cDCE weights
- `interactive_map.html` – Map with layer toggle
- `summary_table.png` – Metrics table

## Try the map
Open `interactive_map.html` in a browser. Use checkboxes (top-right) to toggle layers on/off.

## Reference
Pfeifer, T., Lange, S., & Protzel, P. (2017). Dynamic Covariance Estimation - A Parameter Free Approach to Robust Sensor Fusion. *MFI 2017*.
The paper is attached with this repo named as : MFI2017.pdf

<img width="597" height="919" alt="MAp" src="https://github.com/user-attachments/assets/b7d77ca9-ba90-45a1-9269-97c5b76f17c9" />

