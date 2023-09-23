# Hazardous Gas Leakage Detection using Nanosaur and Jetson Nano

The aim of the project was to do modifications to [Nanosaur](https://nanosaur.ai/) by [Raffaello Bonghi](https://rnext.it/). We designed a custom Printed Circuit Board to mount the three gas sensors on Jetson Nano. We also designed a 3D-printed camera housing to mount a binocular camera with an integrated IMU. On the software front, we deployed [ORBSLAM-2](https://github.com/raulmur/ORB_SLAM2) on the hardware to do Visual-SLAM.

The high level idea was to use the data from gas sensors and localization from VSLAM to find locations with a higher gas concentration, which corresponds to regions close to the leakage. 
<p align="center">
<img src="web_ss.PNG" alt="drawing" width="400"/>
<img src="slam.gif" alt="drawing" width="400"/>
<img src="front_right_con.jpg" alt="drawing" width="400"/>
</p>

Please find details in our [report.](report.pdf)

We were awarded the Best Project Award for our work, and it was featured on [Wadhwani Electronics Laboratory's YouTube Channel!](https://youtu.be/vspevFlvx1A)
