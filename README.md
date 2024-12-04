# POSE-ANGLE-ANALYSIS-FOR-ILLEGAL-CHUCKING-DETECTION-IN-BOWLING
## 1. Overview
### Objective
The project focuses on using Computer Vision (CV) techniques to detect illegal chucking actions in bowlers by analyzing their bowling pose angles. By employing TensorFlow in Google Colab, the system identifies potentially illegal actions based on key pose parameters, providing valuable insights for performance analysis and regulatory compliance.

# SAMPLE IMAGE
![pose annotation](https://github.com/user-attachments/assets/e96b7a27-edfc-40b9-8266-814ad47bd26f)

### Technology Stack
  * TensorFlow: Used for deep learning-based pose detection and analysis in real-time.
  * OpenCV: Leveraged for image and video processing tasks such as frame extraction, manipulation, and feature detection.
  * Google Colab: Used as the development environment for integrating TensorFlow and OpenCV for pose angle analysis.
## 2. Key Features
### (i). Pose Angle Analysis
  * Pose Estimation: Utilizes pre-trained models (e.g., OpenPose) to detect and track the bowlers' body poses during their bowling action.
  * Angle Calculation: Key joint angles, especially around the elbow and shoulder, are calculated to assess whether a bowler is engaging in an illegal chucking action.
  * Frame-by-Frame Analysis: The video footage of the bowler’s action is processed frame-by-frame to accurately measure the angles at each stage of the bowling action.
### (ii). Illegal Chucking Detection
  * Thresholds for Legal Action: Based on biomechanical research, certain pose angles (e.g., elbow extension) are identified as potentially indicative of an illegal chucking action.
  * Real-Time Feedback: As the bowler performs their action, the system provides real-time feedback on whether their technique is within legal limits or not.
  * Visual Feedback: OpenCV is used to overlay the calculated pose angles on the video frames, offering a clear visual representation of the bowler’s biomechanics.
### (iii). Integration with Image Processing Libraries
  * OpenCV: Helps in pre-processing the video data, detecting the bowler’s motion, and extracting frames for pose analysis.
  * TensorFlow: Powers the deep learning models that process the pose estimation and calculate the key joint angles critical for determining if the bowler is potentially using an illegal technique.
## 3. Benefits
  * Improved Regulatory Compliance: By automatically analyzing bowlers’ actions, the system aids in ensuring that players adhere to the legal standards of bowling.
  * Real-Time Detection: Coaches and officials can receive immediate feedback, allowing them to address issues quickly.
  * Enhanced Player Development: By identifying issues in a bowler’s action, corrective measures can be implemented, improving the player’s performance and reducing injury risks.
## 4. Conclusion
The Pose Angle Analysis system using TensorFlow and OpenCV provides an efficient and accurate tool for detecting illegal chucking actions in bowlers. By integrating advanced computer vision techniques, the system supports real-time performance monitoring, ensuring bowlers maintain legal and optimal techniques.
