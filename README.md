# Monoestatic-mechanic-RADAR
Homemade RADAR with the magnetron of an old microwave

We all know what radar is: that typical antenna with the small green screen that shows us the enemy's position in Hollywood movies. But if you ask anyone how it works, I guarantee that at least 95% won't know the answer.

In this project, my goal is to investigate everything related to radar systems: electromagnetic waves, frequency, targeting algorithms, calculations, 3D design... And finally, to try to build one with inexpensive and readily available materials, such as a microwave magnetron for the transmitter.

I plan to use OnShape for the 3D design of the radar's housing and mechanical parts, a microcontroller programmed in C++ (such as an ESP32 or Arduino if possible) for analyzing received waves compared to emitted waves and for using a target-locking algorithm that I will try to develop myself, an external computer and monitor for displaying the radar from the data sent by the microcontroller, servos such as the MG996R for moving the antenna's X and Y axes, a parabolic reflector made of aluminum around the tip so that the microwaves bounce off the walls and become as parallel to each other as possible to maximize range and efficiency, and a power source for the magnetron, which will be coming from the magnetron's microwave.


