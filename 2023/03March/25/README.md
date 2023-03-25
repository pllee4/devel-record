# 26/03

## Update
- Applied low pass filter on PC for raw data from IMU for angle (pitch) of robot to remove spike (noise).
- Tuning was done based on historical data.
- The difference is shown on the simulated robot below.
- Perhaps futher improvement could be done using moving average or ABT filter.

## With raw data
https://user-images.githubusercontent.com/42335542/226695832-66f9eba3-bc2c-45ba-b257-0ef6f8ce874d.mp4

## With filtered data
https://user-images.githubusercontent.com/42335542/226696142-e8e41334-b0bf-42d2-9075-afdff983a793.mp4