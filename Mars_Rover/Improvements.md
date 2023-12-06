# Mars Rover Improvements 

There are several parts of this prject that could have been improved.

The PID tuning should have been done more frequently after the first run. Group 1 did not fully understand the concept of PID tuning before attempting to tune so each mission was ran fully and adjustments were made in between runs; this stategy took a lot of time. If Group 1 would have spent all of the testing time live tuning, a lot more time would have been invested into tuning and most likely would have yielded better results. 

An improvement to the additional sensor data would be aligning the timing. The DHT-11, the additional sensor, was set to record data from the time it recieved power. The DHT-11 was operated by an Arduino MEGA. Ideally, this device should have been triggered by the Raspberry Pi. Group 1 attempted to trigger the Arduino with a servo signal from the Raspberry Pi, but was unable to send an additional servo signal indicating the start of the mission. Signaling the start of the mission would allow the DHT-11 data to start recording at the start of the mission, alligning the timing. 