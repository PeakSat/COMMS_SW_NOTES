#### Description of Action
GNSS Data in the appropriate form are stored to eMMC memory.
#### Moment of Action
Periodically. Depends on the refresh rate that is needed for the TLE generation.
#### Why
The TLE generation algorithm requires more data than what is produced during the RF pass. By periodically storing them, we gather sufficient GNSS information for generating the TLE.