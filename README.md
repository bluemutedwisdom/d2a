# d2a

Converts DTS audio streams to AC3 in a given MKV file,
preserving their order.

## Requirements

* mkvmerge, mkvextract (part of mkvtoolnix)
* ffmpeg
* enzyme python lib (https://github.com/Diaoul/enzyme)

## Usage

    $ ./d2a -f filename.mkv

## Notes

Puts temporarly data into "working-TIMESTAMP" in the current
working directory. It does not delete any of the processed
files nor delete the original - make sure to reserve additional
space for that.
