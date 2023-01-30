# obstacle-avoider
The aim of this project is to implement an obstacle avoiding robot using
ultrasonic sensor and Arduino,

 When the robot is powered on, both the motors of the robot will run normally
and the robot moves forward. During this time, the ultrasonic sensor

continuously calculates the distance between the robot and the reflective surface.
 If the distance between the robot and the obstacle is less than 15cm, the Robot
stops and scans in left and right directions for new distance using Servo Motor
and Ultrasonic Sensor. If the distance towards the left side is more than that of
the right side, the robot will prepare for a left turn. But first, it backs up a little
bit and then activates the Left Wheel Motor in reversed in direction and vice
versa.
