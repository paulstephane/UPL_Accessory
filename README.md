
## Purpose

The **UPL96ETL** by ECDesigns is a high fidelity audio source that plays music files stored on USB keys.

https://www.ecdesigns.nl/en/blog/upl96etl

Music files must comply with the following formats:

- files are stored in folders whose first two digits must be 01 to 99
- file names must also start with 01 to 99
- files must be in WAV format, with id3v2 tags only
- id3v2 tags should contain at minimum the artist, album, title, track number
- first file of each folder can contain an image (album cover art, preferably in small format)

The program available in this repository is designed to *assist* in copying your music files to USB keys in a format compatible with the use of the UPL96ETL. It is written with Livecode community edition (open source).

It has only been tested on Windows.


## Prerequisites

The  the following programs must be installed: Kid3 (music tagger) and dBpoweramp Music Converter (audio file conversion)

https://kid3.kde.org/
    
https://www.dbpoweramp.com/dmc.htm

## Operation

On startup, the settings card is displayed:




- click on "List Drives" to refresh the list of removeable media, and select one in the list
- optionally locate the database file "upl96etl.db" by clicking on "UPL Database". 
- locate the program file "Kid3-cli.exe" on your computer by clicking on "Kid3-cli"
- locate the program "CoreConverter.exe" on your computer by clicking on "CoreConverter"

Click on "OK" to display the second card.

Note: the database file is updated by the ECDesigns application (https://www.ecdesigns.nl/en/blog/uplremote-software) when inserting keys into the UPL96ETL.
If the database file is indicated above, the USB key will be removed from the database when adding new folders, and will trigger an automatic update when inserting it into the UPL96ETL.







