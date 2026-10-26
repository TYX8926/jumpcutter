# Heads up!

This program was forked and modified back in 2021, and I have no means of really developing it further. However, it may be used in a future project that will involve video editing (psst)... Who knows?

In the meantime, this repository is here for others to clone and download and make their own. The original description is preserved with broken links fixed. For what was improved in this fork over the original:
- Quality-of-life CLI interaction improvements (instead of just a bunch of switches, there's a navigation wizard + improved live status)
- More efficient storage usage during jumpcutting (after all video frames are extracted, necessary frames of videos are moved into another directory instead of copied)
- Performance metrics visibility at the end of a jumpcut session; includes memory usage, CPU usage, and relevant data (mostly for diagnostics)
- Other miscellaneous performance improvements that I don't quite remember of

---

# JumpCutter

Automatically cuts out silent parts of videos.
This is forked from the original JumpCutter made by **carykh**.

Explanation can be found here: https://www.youtube.com/watch?v=DQ8orIurGxw

## Information

This forked version of JumpCutter is designed to run more efficiently and jumpcut videos faster, along with a bit more simplicity. It should be noted that it may take a long time for the jumpcutter to finish, depending on your computer's hardware.

It is strongly recommended to check the duriation of the video before attempting to jumpcut. The longer the video, the more space it could take up, as it exports every frame in the video as a **.jpg** image file.

## Download

### Python Script
Use Git to clone the repository to a folder using `git clone https://github.com/TYX8926/jumpcutter`.

### Executable File
You can download the executable version of the file [here](https://github.com/TYX8926/jumpcutter/releases).

## Requirements

### Python Script

You will need **Python 3.7.3** and **FFmpeg** for this script to work.

Other operating systems and Python versions have not been tested to work with this script, and they are **untested**.

### Executable File

You will need **FFmpeg** for the executable version to work, with a computer running **Windows 10**.

Other Windows operating systems may or may not work with this, and they are also **untested**.
