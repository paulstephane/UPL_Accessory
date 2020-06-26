
## Objective

The **UPL96ETL** by ECDesigns is a music player that provides high fidelity and works only with WAV files stored on USB Keys:

https://www.ecdesigns.nl/en/blog/upl96etl

This simple program is designed to assist in copying your music files to USB keys in a format compatible with the use of the UPL96ETL. It is written with Livecode community edition. The source files are provided here so that the program can be customized if required. It has only been tested on Windows.

It requires installing Kid3 and dBpoweramp Music Converter:

https://kid3.kde.org/
https://www.dbpoweramp.com/dmc.htm

## Operation

Music files copied to USB keys must comply with the following formats:

- files are stored in folders whose first two digits must be 01 to 99
- file names must also start with 01 to 99
- files must be in wav format, with id3v2 tags only
- first file of each folder can contain an image (album cover art, preferably in small format)
- id3v2 tags should contain at least the artist, album, title, track tags


