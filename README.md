# vinyl_records_restoration

Vinyl records restoration interview task.

Once upon a time I found this amazing interview task and providing here example images and description of the task. 

## Task

### Description

In [images](./images) folder you can find images of vinyl records.  Each image of vinyl record 
contains few seconds of audio recorded on 120 rpm. Each record is a spiral, which starts on outer part of a disk
and ends inside. On a recording you will have a human voice reading decimal digits. Last two digits are summ of 
all previous digits modulo 10.

Example:

```
1 2 3 4 0 0
```

### Goal

Main goal is to develop an application to decode audio from images of vinyl records.

Requirements:

1. Application should have support of command line argument which would specify a path to an image of vinyl record.
2. Application should save output audio file in a same folder with image. Audio file should be in format 
supported by common audio player software.
3. Audio file should contain intelligible audio, decoded from image of vinyl record.
4. Solution should have:
   - Application source code.
   - Compiled and ready-to-use executable.
   - Decoded audio files.
   - Text files with sequence of decimal digits which you got from audio files.
   - Technical description of the application.

Max time to achieve all goals: 5 days.
