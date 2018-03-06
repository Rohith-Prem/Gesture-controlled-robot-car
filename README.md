# Gesture-controlled-robot-car
/***Gesture controlled robot car using Arduino UNO and Accelerometer.***/
Add the VirtualWire library to your Arduino IDE library folder.
Readings of accelerometer has to be studied in real time to obtain range for each direction.Given ranges is dependent on hardware and other factors.
Small time lag between gesture and corresponding action will be present.It has been reduced as much as possible.
The 'transmitter' code has to be burned into the Arduino UNO connected to the accelerometer that acts as the transmitter.
The 'reciever' code has to be burned into the Arduino UNO connected to the car,this acts as reciever.
The instruction are transmitted using RF transmitter reciever couple./n

COMPONENTS USED:/n
Arduino UNO x2
RF ASK module 433/434 Mhz Reciever Transmitter Pair
ADXL335 Triple axis accelerometer
L293D Motor Driver IC
DC Motors x4
