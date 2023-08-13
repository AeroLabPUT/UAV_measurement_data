UAV configuration

C   A
 \ /
 / \
D   B

folder name:
measuringWindowLength_windowType_rangeStart_rangeStop

file name:
UAVname_sensorRange_FFT_sensorType_measuringWindowLength_windowType_sensor_rangeStart_rangeStop_ABCD.csv

ABCD:
0 - no fault
1 - chipped edge
2 - bent tip


Each line contains (rangeStop - rangeStart + 1)  values for every of 12 sensor axis, i.e. if rangeStop = 36 and rangeStart = 16, there are 252 values in every line, because 21*4*3 = 252
