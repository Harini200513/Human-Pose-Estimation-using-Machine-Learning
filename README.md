# Human-Pose-Estimation-using-Machine-Learning
Human Pose Estimation is a crucial computer vision task that involves detecting and tracking human body landmarks to analyze movement, posture, and gestures. This project implements a real-time pose estimation system using  MediaPipe Pose framework, which is optimized for efficient and lightweight processing on consumer-grade hardware. Unlike deep learning models that require high-end GPUs, this system runs efficiently on CPUs, making it accessible for applications in sports analytics, healthcare monitoring, fitness tracking, human-computer interaction (HCI), and security surveillance.

The core functionality of this project includes real-time pose detection from images and videos, extracting key body landmarks such as shoulders, elbows, knees, and ankles. The system processes input frames, applies the MediaPipe Pose model, and overlays detected landmarks for visualization. Using OpenCV for image/video processing and Matplotlib for visualization, the project ensures smooth and interpretable pose tracking.

One of the main advantages of this implementation is its low computational cost, allowing it to function effectively on devices with limited processing power. However, some challenges remain, including handling occlusions, tracking multiple people in a single frame, and achieving full 3D pose estimation. Future improvements will focus on enhancing occlusion handling, improving multi-person tracking, and integrating depth-sensing technologies for better accuracy.
