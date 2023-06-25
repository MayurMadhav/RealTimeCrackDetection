# Real-Time Crack Detection using Laplacian Filter & Contour Analysis

## Inspiration
The Real-Time Crack Detection project aims to provide a solution for detecting cracks in real-time using computer vision techniques. The inspiration behind this project is to develop an automated system that can assist in the early detection of cracks in structures such as buildings, roads, or infrastructure. By detecting cracks early, appropriate measures can be taken to prevent further damage and ensure the safety of the structures.

## Requirements
To run the Real-Time Crack Detection system, you will need the following:

- Python (version 3.10.0)
- OpenCV (version 4.7.0)
- NumPy (version 1.25.0)

Ensure that the required dependencies are installed before running the system.

## Methodology
The Real-Time Crack Detection system uses computer vision techniques to analyze frames captured from a webcam in real-time. The following steps are involved in the crack detection process:

1. Capture a frame from the webcam.
2. Convert the frame to grayscale for further processing.
3. Apply the Laplacian filter to enhance edges and cracks.
4. Convert the Laplacian image to an 8-bit unsigned integer.
5. Apply thresholding to create a binary image of cracks.
6. Find contours in the binary image.
7. Draw contours on the original frame to highlight the cracks.
8. Display the frame with highlighted cracks in real-time.

The system continuously performs crack detection on each frame received from the webcam, providing real-time feedback on the presence of cracks.

## Results
The Real-Time Crack Detection system has shown promising results in detecting cracks in real-time. It can effectively identify cracks in various structures and highlight them in the captured frames. However, the accuracy and performance of the system may vary depending on environmental conditions, lighting, camera quality, and other factors.

![image](https://github.com/MayurMadhav/RealTimeCrackDetection/assets/86610043/a15044f6-2922-4146-a2b1-499433da3e3a)


## Accuracy
The accuracy of the crack detection system depends on several factors, including the quality of the input frames, the effectiveness of the chosen computer vision techniques, and the threshold values used for crack identification. It is important to note that the system may not detect all cracks or may occasionally produce false positives. Regular calibration, optimization, and testing can help improve the accuracy of the system.

Please note that the Real-Time Crack Detection system is provided as-is, and its accuracy may vary in different scenarios. It is recommended to use this system as a supplementary tool for crack detection and consult with experts for a thorough assessment of structural integrity.

## Contributors
- Mayur C (https://github.com/MayurMadhav)

Feel free to contribute to this project by submitting bug reports, feature requests, or pull requests.
