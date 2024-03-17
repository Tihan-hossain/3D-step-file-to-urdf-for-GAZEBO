# 3D-step-file-to-urdf-for-GAZEBO

# Design 
Design Your Robot with Shapr3D(iPad IOS), SolidWorks, Fushion 360. Save every part in a separate folder it helps to easily modify the robot as needed. Here is one example image I took from my iPad Shapr3D. It's a four-wheel autonomous ground vehicle equipped with IMU, GPS, LIDAR, SharpIR and Sonar Sensors.
<div align="center">
  <img src="https://github.com/Tihan-hossain/3D-step-file-to-urdf-for-GAZEBO/assets/73034571/9f6dca02-27a7-4435-8198-e4a6bc8b3b47" alt="Your Image" width="400"/>
</div>
# Move the Design to Fusion360
N.B. The main body of the Robot must be saved as a base_link or the robot must have a base_link components. After exporting it in step file format open those files in Fushion 360.
<div align="center">
  <img src="https://github.com/Tihan-hossain/3D-step-file-to-urdf-for-GAZEBO/assets/73034571/e0070c79-a444-4070-bad2-b6e0d2f9045d" alt="Youre" width="400"/>
</div>
# Creating Components
Make sure all the parts open as Components, not Bodies. If the files open as a body move those files to components. You can easily do this by right-clicking the mouse over the bodies and selecting *New Components/Create Components From Bodies*
# Robot Orientation 
The origin of Robot in ROS is different than the design software. In ROS the front side of the Robot in is the X-axis, Y-axis in the side, and Z-axis in the upper direction. Also, be careful with the origin point of every component those must be at One Point. How to move the origin in Fushion 360 Here the [Youtube Link](https://youtu.be/XOIHVy08mWs?si=J6FnIkxxXJNq7Lhd).
<div align="center">
  <img src="https://github.com/Tihan-hossain/3D-step-file-to-urdf-for-GAZEBO/assets/73034571/4ca3a5bd-cf9f-442d-8778-737f55daadaa" alt="Youe" width="400"/>
</div>




