## D74A

A collection of notes for setting up and using the Kenwood D74 HT in several modes.

## TOC

- [Setup](#Setup)
	* [Bootstrap Settings](#bootstrap-settings)
	* [Turn on APRS](#turn-on-aprs)

### Setup

#### Bootstrap Settings

Taken from [Don Arnold's TH-D74 Quick Start Setup video](https://youtu.be/aldEwRD4tYw).

| Menu | Configuration | Setting |
|---|---|---|
| 900 | backlight control | set on |
| 950 | time | set UTC (Pacific is -7) | 
| 920 | battery saver | set off |
| 921 | auto power off | set off |
| 404 | gps battery saver | set off |
| 610 | DStar my callsign | enter your callsign |
| 611 | DStar TX message | enter something like "TH-D74" or "Oregon" |
| 506 | APRS Data Band | set B Band |
| 400 | Built in GPS | set on |
| 401 | My Position* | set lat long |
| 510 | APRS Beacon Method | select SmartBeaconing |

\* Optional setting if Built in GPS is set to off.

#### Turn on APRS
1. 	Press Dual A/B on keypad and enter 144.390 for b band freq
2.	Press Function and 5 key
3.	Verify "APRS 12" is shown in display. If not repeat Funtion 5 step until APRS 12 is visible.
4. 	Press keypad number 6 to turn beaconing on. You should see BCON just below APRS 12 in display.

#### Backup and Restore
*	Menu 800 - Config Backup, awill save to the SD card (requires optional SD card, duh)
*	Menu 810 - Config Restore, you can choose your saved config and it will load.

#### Other Important Menu Items
*	Menu 112 - mic gain
*	Menu 200 - Memory Channel List
*	Menu 201 - Group Name
*	Menu 700 - FM Radio
*	Menu 710 - FM Radio List
*	Menu 930-936 Bluetooth items
*	Menu 910-916 - Audio Settings
*	Menu 940 & 941 Customizable PF keys

### D-STAR

### APRS

#### Sending Texts
1. Press Function | New MSG
2. To Field: SMSGTE
3. Message Field: @<PhoneNumberOfRecepient> Body of Message

Example Message
@555-555-5555 This is a test. 

### Frequency Reference

#### Portland Amateur Radio Club

*   146.840 MHz (-600) - The club's main repeater, located in Washington, can reach as far south as Eugene, West to Astoria, East to Hood River and North to Longview.
*   146.940 MHz (-600) - This repeater is located on Mt. Scott. Coverage into the Portland metro area, and South to Salem, is excellent. Currently off the air for repairs.
*   147.180 MHz (+600) 103.5 Hz CTCSS - This repeater located on Mt. Scott and running a Yaesu System Fusion repeater in AMS mode to provide functionality to both analog(with a tone of 103.5) and digital users.
*   144.910 MHz (packet) - The long-running packet node has been replaced with WinLink on the same frequency, connect to W7LT-10. Located on Mt Scott.
*   145.730 MHz (simplex) - This is the traditional PARC home for simplex voice activities.

#### APRS

*   144.390 MHz -- Colombia, Chile, Indonesia, Malaysia, North America, Thailand
*   144.575 MHz -- New Zealand
*   144.640 MHz -- Taiwan
*   144.660 MHz -- Japan
*   144.800 MHz -- South Africa, Europe, Russia
*   144.930 MHz -- Argentina, Uruguay
*   145.175 MHz -- Australia
*   145.570 MHz -- Brazil
*   145.825 MHz -- International Space Station
*   430.5125 MHz -- Netherlands (UHF)
*   432.500 MHz  -- Europe (UHF)

### Reference Links
*   [Portland Amateur Radio Club](http://www.w7lt.org)
*   [Ham Radio School / I Got My License, Now What?](https://hamradioschool.com/i-got-my-license-now-what/)
*   [D-STAR Info](http://www.dstarinfo.com/home.aspx)
*   [D-STAR Users / Last Heard](http://dstarusers.org/lastheard.php)
*   [Amateur Radio Notes / Diving Into D-Star TH-D74A](https://amateurradionotes.com/th-d74.htm)
*   [D-STAR 101](http://www.dstar101.com/basicoperation.htm)
*   [D-STAR Quick Start Guide](http://www.roblocher.com/whitepapers/dstar.html)
*   [Newbie's Guide to D-STAR AU](http://www.dstar.org.au/wp-content/uploads/2015/02/Newbies-Guide-to-D-Star-V2.01.pdf)
*   [WINLINK Global Radio Email](https://winlink.org)
*   [APRS Digipeating and Path Selection](http://wa8lmf.net/DigiPaths/)
 
