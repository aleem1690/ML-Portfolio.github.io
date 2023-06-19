Moving Object Detection in Videos

This project focuses on detecting and highlighting moving objects in a video. Various methods and filters are utilized to achieve 
accurate results. The following techniques were employed and compared to identify the most effective approach:

1. Temporal Median Filter: A filtering technique that computes the median value of corresponding pixels in a series of frames to reduce 
noise and highlight moving objects.
2. Gaussian Mixture Model (GMM): A background subtraction algorithm that models the background as a mixture of Gaussians and identifies 
foreground objects based on pixel intensity deviations.
3. MOG (Mixture of Gaussians): Another background subtraction algorithm that models the background as a mixture of Gaussians and 
distinguishes foreground objects using pixel intensity differences.
4. MOG2 (Improved Mixture of Gaussians): An enhanced version of MOG that adapts the Gaussian mixture model over time to handle changing 
backgrounds more effectively.
5. K-Nearest Neighbors (KNN): A background subtraction algorithm that classifies pixels as foreground or background based on the majority
vote of its neighboring pixels.
6. CNT (Counting-based Neighbourhood Technique): A background subtraction method that leverages a counting-based approach to 
differentiate moving objects from the background.

In addition to these methods, various filters and morphological operations were employed for further noise reduction and object 
enhancement. The following filters were utilized:
- Erosion: A morphological operation that erodes away the boundaries of foreground objects.
- Dilation: A morphological operation that expands the boundaries of foreground objects.
- Opening: A morphological operation that performs an erosion followed by a dilation to remove small noise regions.
- Closing: A morphological operation that performs a dilation followed by an erosion to close small gaps within foreground objects.

Comparison and Evaluation:
After evaluating the different methods and filters, it was found that the Moving Object Detection (MOD) approach yielded the least noise
and provided the most accurate results for highlighting moving objects in the video.

Dependencies:
- Pandas
- OpenCV
- NumPy
- matplotlib

Usage:
1. Install the required dependencies.
2. Preprocess the video data.
3. Implement the different methods and filters for moving object detection.
4. Compare the results and evaluate the accuracy of each approach.
5. Choose the MOD method for the desired noise reduction and highlight moving objects effectively.

Conclusion:
This project successfully detects and highlights moving objects in videos. The comparison of various methods, including the Temporal 
Median Filter, GMG, MOG, MOG2, KNN, and CNT, along with filters and morphological operations, determined that the Moving Object Detection
(MOD) method produced the most accurate and noise-free results. This project can be utilized in various applications such as 
surveillance, object tracking, and video analysis.
