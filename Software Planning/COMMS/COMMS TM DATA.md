#### Description of Action
The COMMS has its own telemetry that has to be transferred to OBC for eventually to be stored to OBC NAND.
#### Moment of Action
Periodically 
#### Questions and Concerns 
Maybe we gather all the information of COMMS at one TM packet and then transmitting it via CAN...or we can send break it into smaller pieces. For example one TM packet with the values of the temperature sensors, another one with GNSS values. The issue here is that the sensor values are being generated with different frequencies.
