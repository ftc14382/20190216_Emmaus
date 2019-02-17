# 20190216_Emmaus
Logs and video rom 20190216 Emmaus High: Green and Gold Qualiier

## Match 5

   Bad position from Vuforia?

   Position:   Blue Left

   Vuforia:      Yes;  (x,y,heading) = (-28.1, 29.8, 57)

   Vuforia used:  No (Rejected because x was too negative, used: (-15.80, 24.30, 72.00)

   Sampled: No. The code fell through to the default (far left) which happened to be where
            the gold was. However, the robot hit a silver.

   Marker: Yes


## Match 9

   This was a perfect run.
   
   Position: Red Left

   Vuforia:  Yes   (18.34, -25.83, -122.61)

   Vuforia used:  Yes

   Sampled:  Yes
   
   Marker: Yes


## Match 14

  This was a  perfect run.

  Position: Blue Left

  Vuforia: Yes (-12.22, 27.44, 64.61)

  Vuforia used:  Yes

  Sampled: Yes

  Marker: Yes

## Match 21

  Vuforia did not see the target. The robot used a default initial position. It worked pretty well for 
  sampling, but went to the wrong position for marker placement and wound up hitting 
  a silver.

  Position: Red Left

  Vuforia: No

  Vuforia used: No, used default (15.80, -24.30, -72.00)

  Sampled: No  (The robot correctly found the gold cube in the center position.)

  Marker: Yes (barely)

## Match 26

  From the log, the DogeCV code sampled the yellow cube at the second position as "345". That is right in the middle of the image. However, the getAligned method on the detector must have returned false. Why it returned false is not clear.

  Position: Red Left

  Vuforia: Yes (17.66, -26.08, -110.34)

  Vuforia used: Yes

  Sampled: No, (The robot looked right at the gold and skipped over it!)
   
  Marker: Yes


