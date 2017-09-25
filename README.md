# LSM6DSM_LIS2MDL_LPS22HB

Initial set of C++ libraries and main Arduino sketch for a custom breakout board using the 6 DoF LSM6DMS accel/gyro, 3DoF LIS2MDL magnetometer, and LPS22HB pressure/temperature sensor along with the EM7180 and an EEPROM to hold its firmware. We haven't built the sensor direvers yet for the EM7180 so initial testing is using the open-source Madgwick sensor fusion filter. The results, after adequate sensor calibration, is three degree rms heading accuracy with this combination of senors, which is superb. We expect to do even better with the EM7180 managing the sensors. Here is the breakout we are using:

