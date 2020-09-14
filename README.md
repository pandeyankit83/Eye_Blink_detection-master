# Eye_Blink_detection
Detect if eye blink or not
An eye is blinking when:
   The eyelid is closed
   We can’t see the eyeball anymore
   Bottom and upper eyelashes connect together
  
We detected the eye, we also detected two lines: an horizontal line and a vertical line crossing the eye.
The size of the horizontal line is almost identical in the closed eye and in the open eye while the vertical line is much longer in the open eye in coparison with the closed eye.
In the closed eye, the vertical line almost disappears.

On python then we create a function to detect the blinking ratio where we insert the eye points and the facial landmark coordinates.
We will then use the ratio number later to detect and we can finally define when the eye is blinking or not.
In this case I found ratio number 5.7 to be the most reiable threshold, at least for my eye.

--shape-predictor : This is the path to dlib’s pre-trained facial landmark detector.
  You can download the detector along with the source code + example videos to this tutorial
  using the “Downloads” section of the bottom of this blog post.
  
  
