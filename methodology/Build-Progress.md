8/11/2025
- Designing the "car" part of the robot (i.e. how to make it move forward and turn smoothly without wobbles)
- Built a differential as a possible plan
- Working on using the motor to steer the front wheels

8/14/2025
- Finished assembly of frame, designed and built front rack-and-pinion steering.
- Attached differential and steering to frame, routed wiring. <br> <br>
<h4>Differential:</h4>
<img src = "https://github.com/mish-chan/ev3_usel/blob/main/methodology/initial_differential.png" alt = "initial differential build">
<h4>Rack-and-pinion Steering:</h4>
<img src = "https://github.com/mish-chan/ev3_usel/blob/main/methodology/initial_steering.png" alt = "initial rack and pinion steering build">
<h4>Full View:</h4>
<img src = "https://github.com/mish-chan/ev3_usel/blob/main/methodology/initial_side_left.png" alt = "view from the left side">
<img src = "https://github.com/mish-chan/ev3_usel/blob/main/methodology/initial_topdown.png" alt = "view from top down">


- Began testing of sensors in a real-world environment.
- The PixyCam has been trained to recognize the green and red blocks using PixyMon V2. The documents related to PixyCam object recognition training can be found here: https://docs.pixycam.com/wiki/doku.php?id=wiki:v2:teach_pixy_an_object_2.
- Using the PixyCam blocks in EV3 Home, a test program was written for the camera to print out "Red Block," "Green Block," or "No Block" based on trained signature recognition as mentioned above.
<img src = "https://github.com/mish-chan/ev3_usel/blob/main/methodology/ev3recongition_simple.PNG" alt = "EV3 Home Simple Recognition Blocks">

8/15/2025
- Attempted to write a program with EV3 Home blocks. However, this proved difficult. Main issues are: hard to read; when the program is not working, it's hard to debug.
- Created pseudo code for a possible way to run a lap in the open challenge: the main method lies in logic similar to line following. Have the vehicle stay a certain distance from the wall, using the distance sensors. Turn when hitting a colored line. If hit blue first, turn left. If hit orange, turn right. -- Logic still to be tested.

8/18/2025
- Moved scripting to EV3 Classroom, still working with block-coding.
- For the first step, we used the color sensor and the gyroscope only, and successfully wrote code to allow the robot to run 3 laps by sensing the mat's colored lines.
- Next step is to have it detect the walls to perform better turns and be flexible to the changing walls in the competition.
- Our build is also too big, working on making it smaller without losing functionality

8/19/2025
- Made a more compact design (still working on this), attempting to allow it to run 3 laps again by fixing both design and code
- Working on new steering designs to allow it to be small enough to fit the competition size requirement while still able to perform high-quality turns
