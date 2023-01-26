UAV configuration

C   A
 \ /
 / \
D   B

folder name:
measuringWindowLength_windowType_sensor_rangeStart_rangeStop

file name:
UAVname_ACCELrange_FFT_measuringWindowLength_windowType_sensor_rangeStart_rangeStop_ABCD.csv

ABCD:
0 - no fault
1 - chipped edge
2 - bent tip


Each line contains (rangeStop - rangeStart + 1)  values for every of 12 sensor axis, i.e. if rangeStop = 52 and rangeStart = 25, there are 396 values in every line, because 28*4*3 = 336

The number of lines is: rawFileLinesNumber/(measuringWindowLength * 2) + 1, i.e. for 86016 lines in the raw file there is 86016/(128 * 2) + 1 = 337

FFT range is from (rangeStart - 1) * (samplingRate/measuringWindowLength) to (rangeStop) * (samplingRate/measuringWindowLength), i.e. if rangeStop = 52, rangeStart = 20, samplingRate = 500 Hz, measuringWindowLength = 128, FFT range is from 74.2 Hz to 203.1 Hz

UAV_measurement_data/Parrot_Bebop_2/FFT_data/128_Hann_20_52 at main · AeroLabPUT/UAV_measurement_data
