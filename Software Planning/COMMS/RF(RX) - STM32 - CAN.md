#### Description of Action
This is how we control the spacecraft using telecommands. A telecommand (TC) is first received from the AT86RF215: [[TC Depacketization]]. The TC is then transmitted via the CAN Bus in the proper format: [[TC format in CAN Bus]].
#### Moment of Action
Depends on how frequently we are receiving TCs.
#### Why
To control the spacecraft and get all the information we need about its condition.
#### Questions and Concerns 
How we will actually receive the data? In the campaign we had the receiver always on and the synchronization was achieved manually by basically transmit data until we received them. One way is by defining an ISR that will be triggered when RF message is received by the AT - has the AT this capability , ask LSF - . Another way is to toggle the RX periodically which is not so efficient.
