# Juggle Lab

Live test page for camera juggle counting (the Footy app's tracking, tuned here first).
Open on a phone, prop it up, juggle. Settings (gear) tune detection live.

Uses Google MediaPipe Tasks Vision (Apache 2.0): EfficientDet-Lite ball detection and pose landmarks.
Test mode: `?src=clip.mp4` plays a video instead of the camera; add `&eval=1` to step through it
and leave stats in `window.evalResult`.
