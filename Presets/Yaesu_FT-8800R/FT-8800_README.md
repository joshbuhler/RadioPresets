# Yaesu FT-8800R Details

Some notes on how I've configured the FT-8800R currently installed in my truck.

## Radio Sides

This radio has two sides to it - a left and right. While each side can can have up to 500 different memory presets for a total of 1000, I’ve opted to duplicate the sides for simplicity. Should the day come where I hit that 501st preset, maybe then I’ll consider not duplicating the sides.

## Mic Buttons

The mic for the FT-8800 has four large preset buttons that can be programmed. I have these configured to do different things that make operating the radio one-handed much easier. (For things like net control, or operating while driving if needed.)

| Button | Function | Description |
| ------ | -------- | ----------- |
| 1 | `LOW` | Cycles through the different levels of power output.
| 2 | `BAND` | Toggles the main band between the left and right side of the radio. |
| 3 | `SCAN` | Begins scanning on the current main band. |
| 4 | `PRI` | Activates priority scanning mode. |

## Hyper Memory Setup

The FT-8800R has six hyper-memory buttons that can store different configurations for the radio, including frequencies and scanning modes. I'm using these to quickly swap between different standard setups. I can't save these in a file that can be restored, so I have to manually set these up on the radio.

### Hyper 1
This sets the radio scanning all memory presets, with the exception of the weather stations and air traffic. Both sides of the radio are actively scanning, but in opposite directions. Left side scanning up, right side scanning down.

### Hyper 2
Basically my favorites list for the Salt Lake area. The left side is monitoring `146.52` , while the right side scans a list of the following stations:

| Left | Right (Scanning) |
| ------------- | ------------- |
| 2M Calling: `146.52` | N7HRC: `449.25` |
|  | 70cm calling: `446.0` |
|  | Farnsworth Peak repeater: `146.62` |
|  | Lake Mountain: `146.76` |
|  | Intertie, Farnsworth link |
|  | Sinbad, Lake Mountain link |

### Hyper 3
Another group of favorites for when I'm home. Mostly simplex that I use to chat with some friends and local repeaters. My most commonly used hyper-memory. I use button #3 as opposed to #1 because of how the radio is mounted in my truck. The button for #3 is pretty easy to hit with my thumb by touch, so I don't really have to look at the radio to go to these presets.

This setting consists of:

| Left (Scanning) | Right (Scanning) |
| ------------- | ------------- |
| 2M Calling: `146.52`  | `146.46`  |
| GTAA: `145.63`  | Farnsworth: `146.62`  |
|  | Lake Mountain: `146.76`  |
|  | N7HRC: `449.25`  |

### Hyper 4
Left is 2M calling (`146.52`), right is scanning NOAA weather stations. Useful when camping and you want to quickly get a weather forecast.

### Hyper 5
Scans FRS/GMRS freqs. Mostly because I think that it's kinda funny to hear what people do when they're out there playing with their "walkie talkies" and think that no one else is listening. Lots of little kids playing around.

### Hyper 6
This setup changes frequently, usually setup for whatever trip I'm currently on. Left is the simplex frequency the group I'm with is currently using, while the right is scanning a list of nearby repeaters, with the addition of the 2M & 70cm calling freqs.


## Memory Banks

Presets are grouped into various related memory banks.

### Bank 1
Presets 1-10. Common frequencies I use. Mostly simplex stuff and repeaters close to home.

### Bank 2
Presets 20-41. Repeaters that belong to the Intermountain Intertie system.

### Bank 3
Presets 45-61. Sinbad repeater system.

### Bank 4
Presets 420-456. Air traffic frequencies, mostly SLC airport, with Ogden, Hill AFB, and generic frequencies. The stuff that gets high.

### Bank 5
Presets 475-496. FRS / GMRS channels.

### Bank 10
Slots 70-79. NOAA weather radio stations.


## Programming Notes / Troubleshooting

### Unable to upload files?
After the factory reset triggered by the MARS mod, the .img file wouldn't upload to the radio from Chirp. Needed to first download the current radio setup from the radio, then copy/paste the preset info from the older .img file. By modifying the new file, I was then able to upload the presets back to the radio.