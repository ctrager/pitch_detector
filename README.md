# pitch_detector

Play your musical instrument (optimized for violin) and see the notes appear on a staff, with color indicating whether your intonation is sharp or flat.

You can try singing also, but I think it's harder to produce a tone that's pure enough for the 
pitch detection algorithm to work well. You can try whistling too.

This works well on my laptop, but not so great on my Android phone. I don't know why. 

Implemented as a single html with all the javascript in it. There's no server.

The app uses the "Yin" pitch detection algorithm. I got the yin code from 
https://github.com/peterkhayes/pitchfinder/blob/master/src/detectors/yin.ts
and/or
https://github.com/ashokfernandez/Yin-Pitch-Tracking/blob/master/Yin.c

As of Jun 6 2020, the above seem to differ in how they size the autocorrelation buffer.
