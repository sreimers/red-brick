Set GPS time as system time
---------------------------

If you can't use NTP (i.e. the RED Brick does not have Internet access), you
can use the GPS Bricklet to set a proper system time.

Upload this program to the RED Brick using Brick Viewer's New Program wizard.
With the following program settings the system time will be corrected every
6 hours:

* 1 of 8:

  * Name: GPS Time
  * Language: Python

* 2 of 8:

  * Add ``gps_time.py``

* 3 of 8:

  * Version 3.x.y
  * Start Mode: Script File
  * Script File: ``gps_time.py``

* 4 of 8: Nothing
* 5 of 8: Default
* 6 of 8:

  * Mode: Interval
  * Interval: 60*60*6 = 21600 seconds (every 6 hours)
  * Continue After Error: Enabled

* 7 of 8: Nothing
* 8 of 8: Start Upload
