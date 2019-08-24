# RadioPresets
Just a backup of the presets I use on my amateur radio gear. Mostly for my own use, but if anyone wants to use it as well, go nuts.

While the number of radios I have may vary, for simplicity, I have the same basic config on each radio, with appropriate changes based on what features the radio support. The setup also changes based on what that radio's primary purpose is. Currently, my main radio is a Yaesu FT-8800R, which is installed in my truck. This one is where you'll find the most detail about my setup, as it's the one I use every day, so it ends up getting the most tweaking and customization.

These presets are based on me living in the Salt Lake Valley, and most of my travel being around Utah. So, if you’re outside Utah, this likely isn’t going to be of much use to you.

# About the Files
There is a folder for each radio’s preset info. The files included are:

* A [CHIRP](http://chirp.danplanet.com/) image file.
* A CSV copy of the preset info, exported from the CHIRP image.
* A reference file of some sort that I use to print out a paper copy of the presets.
* The formatted markdown file used for printing.
* Anything else that seems relevant for that radio.

## Preset Reference Creation
The reference file is created using the following steps:

1. Exporting a CSV file from CHIRP.
2. Import the CSV into Excel, for easy editing. Add any notes or comments, and remove any columns as desired.
3. Export the file as a tab-delimited .txt file.
4. Convert the tab-delimited file to a Markdown table for printing. For this, I use Jesse Donat’s [CSV to Markdown Table Generator](https://github.com/donatj/CsvToMarkdownTable). A live version that can be used to copy/paste the info is available at [https://donatstudios.com/CsvToMarkdownTable](https://donatstudios.com/CsvToMarkdownTable)
5. Edit Markdown file, and print using whatever CSS style you like.

…or, you can also just print directly from the Excel file. Whatever. The Excel version is a lot easier, and involves fewer steps.

# General Notes
The presets are arranged generally the same on both radios at the moment. The FT-8800R has more memory slots, so it has more presets, where the the Baofeng only has 128 memory slots, so it just contains a subset of the items. Generally though, the presets are arranged like so:

## Slots 1-19
These are a mix of favorite repeaters, like Farnsworth Peak, Lake Mountain, Herriman, and the simplex calling frequencies. The others are frequencies used by the Herriman Amateur Radio Club for various things.

## Slots 20-41
Intermountain Intertie repeaters

## Slots 45-61
Sinbad Repeater System

## Slots 65-67
Dixie Linked System in the St. George area

## Slots 70-79
Weather station frequencies

## Slots 106-399
Assorted 2M & 70cm repeaters in Utah & Idaho

## Slots 420-456
Air traffic frequencies, mostly SLC airport, with Ogden, Hill AFB, and generic frequencies. The stuff that gets high. heh.

## Slots 475-496
FRS & GMRS frequencies. While my radios aren't type-accepted to transmit here, sometimes it's nice being to just listen in.


# License
This stuff is available under a Creative Commons Attribution Share Alike 4.0 license. I don’t know that a license is necessary here, or even worthwhile, but I figured that if anyone stumbled across this collection, I wanted it to be clear that I’m cool with you using it.