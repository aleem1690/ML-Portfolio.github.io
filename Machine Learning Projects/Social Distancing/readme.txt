Social Distancing Detection in Videos

This project focuses on detecting individuals who are not following social distancing guidelines in a video where people are working. 
The goal is to identify instances where people are in close proximity to each other and highlight those instances. Various methods and 
filters are utilized to achieve accurate results. The following techniques were employed:

1. Gaussian Mixture Model (GMM): A background subtraction algorithm that models the background as a mixture of Gaussians and identifies 
foreground objects based on pixel intensity deviations.
2. MOG (Mixture of Gaussians): Another background subtraction algorithm that models the background as a mixture of Gaussians and 
distinguishes foreground objects using pixel intensity differences.
3. MOG2 (Improved Mixture of Gaussians): An enhanced version of MOG that adapts the Gaussian mixture model over time to handle changing 
backgrounds more effectively.
4. K-Nearest Neighbors (KNN): A background subtraction algorithm that classifies pixels as foreground or background based on the majority
vote of its neighboring pixels.
5. CNT (Counting-based Neighbourhood Technique): A background subtraction method that leverages a counting-based approach to differentiate
moving objects from the background.

In addition to these methods, various filters and morphological operations were employed for further noise reduction and object 
enhancement. The following filters were utilized:
- Erosion: A morphological operation that erodes away the boundaries of foreground objects.
- Dilation: A morphological operation that expands the boundaries of foreground objects.
- Opening: A morphological operation that performs an erosion followed by a dilation to remove small noise regions.
- Closing: A morphological operation that performs a dilation followed by an erosion to close small gaps within foreground objects.

The detected instances of individuals in close proximity are highlighted by drawing contours around them. Additionally, a warning sign 
is displayed to visually indicate the need for maintaining social distancing.

Dependencies:
- Pandas
- OpenCV
- NumPy

Usage:
1. Install the required dependencies.
2. Preprocess the video data.
3. Implement the different methods and filters for social distancing detection.
4. Draw contours around instances of individuals in close proximity.
5. Display a warning sign to emphasize the importance of maintaining social distancing.

Conclusion:
This project successfully detects instances of individuals not following social distancing guidelines in videos. By utilizing techniques
such as GMM, MOG, MOG2, KNN, and CNT, along with filters and morphological operations, instances of people in close proximity can be 
identified. Drawing contours and displaying a warning sign provide visual cues to promote social distancing measures.
