UAV configuration

C   A
 \ /
 / \
D   B

file name:
UAVname_ACCELrange_GYRO_range_ABCD.csv


ABCD:
0 - no fault
1 - chipped edge
2 - bent tip

Each line contains 24 variables corresponding to the following readings from the sensors:
A_ax, A_ay, A_az, A_gx, A_gy, A_gz, 
B_ax, B_ay, B_az, B_gx, B_gy, B_gz,
C_ax, C_ay, C_az, C_gx, C_gy, C_gz,
D_ax, D_ay, D_az, D_gx, D_gy, D_gz.

The data were presented in [g] for the accelerometer and [dps] for the gyroscope.

Data were taken at a rate of 500 measurements per second.  8616 lines correspond to 172,032 seconds.
