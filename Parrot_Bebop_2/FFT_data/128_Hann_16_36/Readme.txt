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

The number of lines is: rawFileLinesNumber/(measuringWindowLength * 2) + 1, i.e. for 86016 lines in the raw file there is 86016/(128 * 2) + 1 = 337

FFT range is from (rangeStart - 1) * (samplingRate/measuringWindowLength) to (rangeStop) * (samplingRate/measuringWindowLength), i.e. if rangeStop = 36, rangeStart = 16, samplingRate = 500 Hz, measuringWindowLength = 128, FFT range is from 58.6 Hz to 140.6 Hz
