## THUG (TH[-D74] User Group) Notes

- [Setup](#Setup)
	* [Bootstrap Settings](#bootstrap-settings)
	* [Turn on APRS](#turn-on-aprs)
	* [Backup and Restore](#backup-and-restore)
	* [Other Menu Items](#other-menu-items)
- [D-STAR](#d-star)
	* [Digital Repeaters](#digital-repeaters)
- [APRS](#aprs)
	* [Sending Messages to APRS Radios](#sending-messages-to-aprs-radios)
	* [Sending Messages to Cell Phones](#sending-messages-to-cell-phones)
- [Frequency Reference](#frequency-reference)
	* [Portland Amateur Radio Club](#portland-amateur-radio-club)
	* [International APRS](#international-aprs)
- [Reference Links](#reference-links)
	* [General](#general)
	* [APRS](#aprs)
	* [DSTAR](#dstar)

### Setup

#### Bootstrap Settings

Taken from [Don Arnold's TH-D74 Quick Start Setup video](https://youtu.be/aldEwRD4tYw).

To enter each menu press the Menu key and then enter the three digit menu code in the table below. Use the Mode and A/B buttons to select and confirm configuration settings. Text may be entered into form fields using the numeric keypad or the radio's encoder dial. Once the configuration is set press the PTT (Push To Talk) key on the side of the radio to return to the home screen before navigating to the next menu item.

| Menu | Configuration | Setting |
|---|---|---|
| 900 | backlight control | set on |
| 950 | time | set UTC (Pacific is -7) |
| 920 | battery saver | set off |
| 921 | auto power off | set off |
| 404 | GPS battery saver | set off |
| 610 | D-Star my callsign | enter your callsign |
| 611 | D-Star TX message | enter something like "TH-D74" or "Oregon" |
| 506 | APRS Data Band | set B Band |
| 400 | Built in GPS | set on |
| 401 | My Position* | set lat long |
| 510 | APRS Beacon Method | select SmartBeaconing |

\* Optional setting if Built in GPS is set to off.

#### Turn on APRS
1. 	Press Dual A/B on keypad and enter 144.390 for b band frequency
2.	Press Function and 5 key
3.	Verify "APRS 12" is shown in display. If not repeat Function 5 step until APRS 12 is visible.
4. 	Press keypad number 6 to turn beaconing on. You should see BCON just below APRS 12 in display.

#### Backup and Restore
*	Menu 800 - Config Backup, will save to the SD card (requires optional SD card, duh)
*	Menu 810 - Config Restore, you can choose your saved config and it will load.

#### Other Menu Items
*	Menu 112 - Mic Gain
*	Menu 200 - Memory Channel List
*	Menu 201 - Group Name
*	Menu 700 - FM Radio
*	Menu 710 - FM Radio List
*	Menu 930-936 Bluetooth items
*	Menu 910-916 - Audio Settings
*	Menu 940 & 941 Customizable PF keys

### D-STAR

#### Digital Repeaters

The TH-D74A can connect to DSTAR repeaters to route voice and data traffic around the country and the rest of the world. Before connecting to other DSTAR users the TH-D74 must first connect to a local DSTAR Repeater. A list of the available D-STAR repeaters is maintained by [D-STAR Info site](http://www.dstarinfo.com/repeater-list.aspx).

##### Connecting to a Digital Repeater

If a repeater list is already loaded on your radio you can discover nearby repeaters by pressing and holding the down navigation control button. After a moment a screen will appear. Use the navigation control to select "Find Nearby Repeaters. Once you've selected the desired repeater...

### APRS

#### Sending Messages to APRS Radios
1. Press Function -> New MSG
2. To Field: \<ReceipientCallsign\>
3. Message Field: Body of Message

#### Sending Messages to Cell Phones
1. Press Function -> New MSG
2. To Field: SMSGTE
3. Message Field: @\<PhoneNumberOfRecepient\> Body of Message

Example Message
@555-555-5555 This is a test.

### Frequency Reference

#### Portland Amateur Radio Club

*   146.840 MHz (-600) - The club's main repeater, located in Washington, can reach as far south as Eugene, West to Astoria, East to Hood River and North to Longview.
*   146.940 MHz (-600) - This repeater is located on Mt. Scott. Coverage into the Portland metro area, and South to Salem, is excellent. Currently off the air for repairs.
*   147.180 MHz (+600) 103.5 Hz CTCSS - This repeater located on Mt. Scott and running a Yaesu System Fusion repeater in AMS mode to provide functionality to both analog(with a tone of 103.5) and digital users.
*   144.910 MHz (packet) - The long-running packet node has been replaced with WinLink on the same frequency, connect to W7LT-10. Located on Mt Scott.
*   145.730 MHz (simplex) - This is the traditional PARC home for simplex voice activities.

#### International APRS

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

#### General
*   [Portland Amateur Radio Club](http://www.w7lt.org)
*   [Ham Radio School / I Got My License, Now What?](https://hamradioschool.com/i-got-my-license-now-what/)
*   [WINLINK Global Radio Email](https://winlink.org)

#### APRS
*   [APRS Digipeating and Path Selection](http://wa8lmf.net/DigiPaths/)

#### DSTAR
*   [D-STAR Info](http://www.dstarinfo.com/home.aspx)
*   [D-STAR Users / Last Heard](http://dstarusers.org/lastheard.php)
*   [Amateur Radio Notes / Diving Into D-Star TH-D74A](https://amateurradionotes.com/th-d74.htm)
*   [D-STAR 101](http://www.dstar101.com/basicoperation.htm)
*   [D-STAR Quick Start Guide](http://www.roblocher.com/whitepapers/dstar.html)
*   [Newbie's Guide to D-STAR AU](http://www.dstar.org.au/wp-content/uploads/2015/02/Newbies-Guide-to-D-Star-V2.01.pdf)
*   [DSTAR Web Calculator](http://www.dstarinfo.com/Calculator/DSTAR%20Web%20Calculator.aspx)
