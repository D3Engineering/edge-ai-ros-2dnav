# edge-ai-ros-2dnav

2dnav package - contains all autonomous driving parameters & costmap information. To use this package "standalone",
one must launch move_base.launch + the motor controller (+odometry, if not included), then send move-base goals
to the robot (through any tool such as rviz).

(There is some unused obstacle avoidance code as well that would need fine-tuning.)
