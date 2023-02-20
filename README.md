# Localization of Quadrotor

A reliable state estimation technique is essential for estimating the state of a quadrotor using different sensors. The Kalman Filter was used to fuse data from various sensors, including the Inertial Measurement Unit (IMU), Vicon (Motion tracking cameras), and Visual Odometry (Optical Flow). The project is divided into three parts. The first part (EKF-MAV) involves implementing the Extended Kalman Filter (EKF) to combine data from the IMU and Vicon. The second part (MAV-PoseVision) demonstrates the effectiveness of RANSAC in visual odometry for removing outliers. Lastly, the third part (UKF-MAV) illustrates the effectiveness of the Unscented Kalman Filter (UKF) in fusing data from optical flow and IMU.

<p float="left">
  <img src="assets/KLT_tracker_ORB.gif" width="400"/>
  <img src="assets/KLT_tracker_ORB2.gif" width="400"/> 
</p>
<p align = 'center'>
  <em>Kanade–Lucas–Tomasi(KLT) feature tracker using ORB</em>
</p> 
