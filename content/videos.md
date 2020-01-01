+++
title = "Videos"

lastmod = "2019-01-20"
description = "Music videos, audio visualizers, and tutorials"
keywords = ["video", "visualizer", "animation", "music", "audio", "song"]
+++

## Audio Visualizers

I've uploaded lots of stuff to YouTube, so I'll just embed a few of them which
I think you might find mildly interesting. Most of them are just visualizers for
some of my songs. I'm not in the game of making music videos, but I figured it'd
be nice to look at something more... "alive" than a still photo or album art.

<center>
{{< youtube id="videoseries?list=PLMVZ5xEDwpObsQ2GND2og2TwvniWRG28m" >}}
</center>


I was able to hack together a [Blender](//www.blender.org/) script to
generate some moving bars  automated/controlled by the volume of the audio at
a given frequency. Ideally this should be an FFT, but I was new to both
[Python](//www.python.org/) and [Blender](//www.blender.org/)
when I wrote the script and used some embedded features in Blender to achieve
a vaguely similar effect.

Someday when I have time (and remember), I want to
re-write that script to use [NumPy](//www.numpy.org/) and run a real FFT
on the audio. This should make the bars look a lot more accurate.
