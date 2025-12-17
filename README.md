\# ROS2 Nav2 Autonomous Navigation (Custom Behavior Tree)



This package contains my custom Nav2 Behavior Tree setup for stable autonomous navigation, including recovery when the robot path is blocked.



\## Demo

🖼 Screenshot: `screenshot`  

🎥 Video: (add link here)



\## What’s inside

\- `behavior\_trees/`  

&nbsp; Base BT used in Nav2

\- `behavior\_trees\_custom/`  

&nbsp; Custom BT variants (Navigate Through Poses + recovery)

\- `nav2\_params/`  

&nbsp; Nav2 parameter overrides to load the custom BT



\## Quick run (high level)

1\. Launch simulation (Gazebo)

2\. Launch Nav2

3\. Set initial pose in RViz

4\. Use \*\*Navigate Through Poses\*\* in RViz and send waypoints



\## Notes

\- Verified by reading the active BT path using:

&nbsp; `ros2 param get /bt\_navigator default\_nav\_to\_pose\_bt\_xml`

&nbsp; and `default\_nav\_through\_poses\_bt\_xml`



