# edge-ai-ros-2dnav

This package is heavily based on the 2dnav ros tutorial:
http://wiki.ros.org/navigation
http://wiki.ros.org/costmap_2d

2dnav package - contains all autonomous driving parameters & costmap information. To use this package "standalone",
one must launch move_base.launch + the motor controller (+odometry, if not included), then send move-base goals
to the robot (through any tool such as rviz).

(There is some unused obstacle avoidance code as well that would need fine-tuning.)


