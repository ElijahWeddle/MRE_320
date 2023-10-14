# Overview

The MPU6050 sensor uses capacitors to measure linear acceleration in 3 dimensions. and angular acceleration in 3 axes. The system contains a mass held in position by springs that contains a potential difference to a fixed reference component. When the MPU6050 sensor is accelerated, the mass will want to stay at rest which will cause a change in distance between the reference and the mass, increasing the capacitance. The angular accelerometer works similarly by taking advantage of the Coriolis effect, also known as the centripetal force which is due to the normal acceleration from rotational motion. For this project, we are only focusing on linear acceleration in one dimension. 

***Testing Process***
The data was collected using a pulley system and car. The testing unit was attached to the car and a known weight was tied to a string that was wrapped around a pulley hanging off the edge of a table. 

Newton's 2nd Law of Motion was used to calculated the known acceleration that was compared to the tested value. The mass of the block multiplied by the acceleration of gravity equals the mass of the car and block together multiplied by their shared acceleration. The car and block experience the same acceleration due to the string that ties them together into one system. 

The mass of the string and friction were not included in the calculations. The string mass and the rolling friction between the car's wheels and table as well as the wheels and axel were considerably small and therefore could be neglected. . 