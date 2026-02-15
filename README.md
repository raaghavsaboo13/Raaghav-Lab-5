# Face Detection & Clustering

## Aim
The aim of this project is to develop a machione learning and computer vision algorithm that detects faces from an image using "Haar Cascade" classifiers, to extract color-based features in the HSV color space, then using the K-Means algorithm which is a clustering technique which uses distance as a metric to cluster objects.


## Methodology
- Read the image using OpenCV and convert BGR to grayscale for face detection.
- Detect faces using `haarcascade_frontalface_default.xml`.
- Convert the detected face regions to HSV color space.
- Extract features: Mean Hue and Mean Saturation
- Apply K-Means clustering on extracted features.
- Predict the cluster label for template image.
- Visualize the clusters using Matplotlib with face thumbnails.


## Key Findings
- Hue–Saturation features enable grouping of faces based on skin tone similarity.
- K-Means clustering provides us with a distance-based approach for categorization.
- Proper color space conversion significantly affects how well the features are extracted.
- Annotated visualization makes it easier to understand the clustering results.


## Conclusions
This project showcases how distance-based machine learning techniques can be integrated with traditional computer vision methods to perform meaningful visual analysis. We combine face detection, feature extraction in HSV space, and K-Means clustering, this projected taught me the importance of, preprocessing the data, feature representation and visualization in building easy to understand machine learning projects.


## Results
<img width="1282" height="855" alt="Screenshot 2026-02-12 at 4 23 58 PM" src="https://github.com/user-attachments/assets/8093b6cb-0f8f-404c-b4d0-d5b1072aeff4" />
<img width="397" height="396" alt="Screenshot 2026-02-15 at 7 01 30 PM" src="https://github.com/user-attachments/assets/bdfafe0d-4ea5-437d-a6eb-f9d815eaf95b" />

<img width="1023" height="551" alt="Screenshot 2026-02-15 at 7 31 34 PM" src="https://github.com/user-attachments/assets/50bc6ba5-e54f-4d37-b7e8-57fd4ad9e143" />
<img width="1015" height="557" alt="Screenshot 2026-02-15 at 7 31 50 PM" src="https://github.com/user-attachments/assets/448db360-e9a8-4cbd-b16f-46763bb4d2e9" />

<img width="1000" height="555" alt="Screenshot 2026-02-15 at 7 32 15 PM" src="https://github.com/user-attachments/assets/17c9c75a-0b19-41c1-905a-1cb6d858526b" />
<img width="1062" height="566" alt="Screenshot 2026-02-15 at 7 32 31 PM" src="https://github.com/user-attachments/assets/a8b12e2d-bc4a-43ef-bfb8-99040f509c3d" />
