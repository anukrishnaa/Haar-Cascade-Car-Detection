# Haar-Cascade-Car-Detection
Car Detection using OpenCV and Haar Cascades This guide details how to perform car detection in images or videos using Haar Cascades, a popular object detection method implemented in OpenCV (Open Source Computer Vision Library).


Vehicle Detection using Haar Cascade Classifier in Video
Project Overview
This project demonstrates the implementation of a Haar Cascade Classifier to detect vehicles in videos using OpenCV. It aims to detect and annotate vehicles with bounding boxes in real-time video streams.

Features
Haar Cascade Classifier: Utilizes a pre-trained XML file (haarcascade_vehicle.xml) for vehicle detection.
Video Processing: Reads and processes a video file (Main Project_Car Detection_video.avi) to detect vehicles frame by frame.
Visualization: Draws bounding boxes around detected vehicles on each frame.
User Interaction: Supports user interaction to exit the video display by pressing the Esc key.


Prerequisites


Python environment with OpenCV installed.
Access to a compatible video file for testing (Main Project_Car Detection_video.avi).
Usage
Installation: Ensure Python and OpenCV are correctly installed in your environment.
Execution: Run the script to initiate vehicle detection in the specified video.
Output: View the processed video with annotated vehicle detections.

Considerations

Accuracy: Haar Cascade classifiers provide efficient detection but may have limitations under varying lighting and vehicle conditions.
Customization: Parameters such as scale factor and minimum neighbors can be adjusted for optimal detection performance.
Further Enhancements: Consider exploring deep learning approaches for improved accuracy in complex scenarios.

Conclusion

This project showcases the implementation of vehicle detection using a classical computer vision technique. It serves as a foundational example for understanding object detection in real-world applications.

