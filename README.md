Any improvement or suggestion is welcomed here! I did my best  :)


:q
exit()
## Live Interactive Map
**View the map here:** https://prakash023.github.io/GNSS-Smoothing-with-DCE---Potsdamer-Platz/

## Results
- Raw GNSS RMSE: 5.88 m
- DCE Smoothed RMSE: 5.87 m
- Improvement: 0.2%


error_comparison.png - error over time
- trajectory_comparison.png - path comparison  
- weight_function.png - cDCE weights
- interactive_map.html - map with layer toggle (checkboxes in top-right)
- summary_table.png - metrics


  ## Map Controls
Open interactive_map.html in your browser. Use the checkboxes in the top-right corner to turn layers on/off:
- Ground Truth
- Raw GNSS  
- DCE Smoothed
- High Error Points

- 
Paper got ~50% with UWB+odometry. My data is GNSS only in urban canyon. DCE doesnt help here more with this case.

