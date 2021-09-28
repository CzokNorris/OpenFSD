# OpenFSD
Step by step towards open source full self driving

Roadmap:
1. Reverse engineer the Panda and make it open source.
2. Make a cheaply manufacturable version of the Comma pedal open source (components on only one side,...). 
3. Stereo Camera Pods which stream via GStreamer (current prototype Gstreamer pipeline has only 20ms of delay end-to-end including my 1ms display).
  Stereo Camera pods are at least needed for mounting under the rear view mirror (here 4 cameras per pod), in the back (two cameras), in the front (two cameras).
  
4. Work on auto-overtake (includes auto-lane-change)
5. Work on an aggregated model that takes all the camera streams and creates a Vecor-representation of the surroudnings with all the relevant things in it.
