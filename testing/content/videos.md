+++
title = "Videos"
description = "Music videos, audio visualizers, and tutorials"
keywords = ["video", "visualizer", "animation", "music", "audio", "song"]
+++

## Audio Visualizers

I've uploaded lots of stuff to YouTube, so I'll just embed a few of them which
I think you might find mildly interesting. Most of them are just visualizers for
some of my songs. I'm not in the game of making music videos, but I figured it'd
be nice to look at something more... "alive" than a still photo or album art.

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/RSRnktucY5c?list=PLMVZ5xEDwpObsQ2GND2og2TwvniWRG28m" frameborder="0" allowfullscreen></iframe>
</center>

I was able to hack together a Blender script to generate some moving bars 
automated/controlled by the volume of the audio at a given frequency. Ideally
this should be an FFT, but I was new to both Python and Blender when I wrote
the script and used some embedded features in Blender to acheieve a vaguly similar
effect.

Someday when I have time and am not feeling burned out by my day-job, I want to
re-write that script to use NumPy and run a real FFT on the audio. This should
make the bars look a lot more accurate.