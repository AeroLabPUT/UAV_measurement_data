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


Each line contains (rangeStop - rangeStart + 1)  values for every of 12 sensor axis, i.e. if rangeStop = 104 and rangeStart = 40, there are 780 values in every line, because 65*4*3 = 780

The number of lines is: rawFileLinesNumber/(measuringWindowLength * 2) + 1, i.e. for 86016 lines in the raw file there is 86016/(256 * 2) + 1 = 169

FFT range is from (rangeStart - 1) * (samplingRate/measuringWindowLength) to (rangeStop) * (samplingRate/measuringWindowLength), i.e. if rangeStop = 104, rangeStart = 40, samplingRate = 500 Hz, measuringWindowLength = 256, FFT range is from 76.2 Hz to 203.1 Hz
