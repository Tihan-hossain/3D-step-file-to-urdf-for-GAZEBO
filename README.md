# 3D-step-file-to-urdf-for-GAZEBO

# Design 
Design Your Robot with Shapr3D(iPad IOS), SolidWorks, Fushion 360. Save every part in separate folder its help to easily modify the robot per needed. Here is one example image I took from my ipad Shapr3D. Its a four wheel autonomous ground vehicle equiped with IMU,GPS, LIDAR, SharpIR and Sonar Sensors.
<div align="center">
  <img src="https://github.com/Tihan-hossain/3D-step-file-to-urdf-for-GAZEBO/assets/73034571/9f6dca02-27a7-4435-8198-e4a6bc8b3b47" alt="Your Image" width="400"/>
</div>
N.B. The main body of the Robot must be saved as a base_link or the robot must have a base_link named part. After exporting it in step file format open those files in Fushion 360.
<div align="center">
  <img src="https://github.com/Tihan-hossain/3D-step-file-to-urdf-for-GAZEBO/assets/73034571/e0070c79-a444-4070-bad2-b6e0d2f9045d" alt="Youre" width="400"/>
</div>

Make sure all the parts open as Components, not Bodies. If the files open as a body move those files to components. You can easily do this my right-clicking the mouse over the bodies and selecting *New Components*
