# LSM6DSM_LIS2MDL_LPS22HB

Initial set of C++ libraries and main Arduino sketch for a custom breakout board using the 6 DoF LSM6DMS accel/gyro, 3DoF LIS2MDL magnetometer, and LPS22HB pressure/temperature sensor along with the EM7180 and an EEPROM to hold its firmware. We've built the sensor drivers for the EM7180 so initial testing is underway. 

We also have a production version without the EM7180 for using the open-source Madgwick sensor fusion filter. The result, after adequate sensor calibration, is three degree rms heading accuracy with this combination of sensors, which is superb. We expect to do even better with the EM7180 managing the sensors. 

Here is the EM7180-based breakout we are using:

![LAM6DSM pcb](https://user-images.githubusercontent.com/6698410/30790075-8c55dc62-a15e-11e7-9288-fa3ce5eb736f.jpg)

The design files are [available](https://www.oshpark.com/shared_projects/80BmcUBS) in the shared space at OSH Park.

Here is the production version with just the three ST sensors:

![AllST](https://user-images.githubusercontent.com/6698410/33967305-babe2094-e017-11e7-83fb-83cab8c660f8.jpg).

[This](https://www.tindie.com/products/onehorse/all-st-motion-sensor-breakout-board/) is available for sale at Tindie.
