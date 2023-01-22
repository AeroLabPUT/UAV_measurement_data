UAV configuration

C   A
 \ /
 / \
D   B

file name:
UAVname_ACCELrange_GYROrange_ABCD.csv

ABCD:
0 - no fault
1 - chipped edge
2 - bent tip

Each line contains 96 characters, corresponding to 48 bytes in HEX format. 
These are data sequentially from the IMU registers. 2 registers (H-MSB and L-LSB) for each accelerometer axis and 2 registers for each gyroscope axis): 
A_ACCEL_x_H, A_ACCEL_x_L, A_ACCEL_y_H, A_ACCEL_y_L, A_ACCEL_z_H, A_ACCEL_z_L, A_GYRO_x_H, A_GYRO_x_L, A_GYRO_y_H, A_GYRO_y_L, A_GYRO_z_H, A_GYRO_z_L, 
B_ACCEL_x_H, B_ACCEL_x_L, B_ACCEL_y_H, B_ACCEL_y_L, B_ACCEL_z_H, B_ACCEL_z_L, B_GYRO_x_H, B_GYRO_x_L, B_GYRO_y_H, B_GYRO_y_L, B_GYRO_z_H, B_GYRO_z_L, 
C_ACCEL_x_H, C_ACCEL_x_L, C_ACCEL_y_H, C_ACCEL_y_L, C_ACCEL_z_H, C_ACCEL_z_L, C_GYRO_x_H, C_GYRO_x_L, C_GYRO_y_H, C_GYRO_y_L, C_GYRO_z_H, C_GYRO_z_L, 
D_ACCEL_x_H, D_ACCEL_x_L, D_ACCEL_y_H, D_ACCEL_y_L, D_ACCEL_z_H, D_ACCEL_z_L, D_GYRO_x_H, D_GYRO_x_L, D_GYRO_y_H, D_GYRO_y_L, D_GYRO_z_H, D_GYRO_z_L.

Data were taken at a rate of 500 measurements per second.  8616 lines correspond to 172,032 seconds.
