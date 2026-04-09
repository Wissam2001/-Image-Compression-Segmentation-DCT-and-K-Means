# Image Compression & Segmentation: DCT and K-Means from Scratch 🖼️
This project was developed as a Master's Lab project in Computer Vision focusing on two fundamental image processing techniques implemented entirely from scratch:

Discrete Cosine Transform (DCT) - A lossy image compression algorithm (similar to JPEG) that transforms images from spatial to frequency domain

K-Means Clustering - An unsupervised segmentation algorithm that partitions images into K distinct regions based on pixel intensity

The project features an interactive Tkinter GUI allowing users to upload images, adjust parameters (number of clusters, cluster selection), and visualize compression and segmentation results in real-time.

🎯 Project Objectives
Understand DCT-based compression - Master the mathematics of frequency domain transformation and quantization

Implement DCT/IDCT from scratch - Build 2D Discrete Cosine Transform without using library implementations

Implement JPEG-style compression pipeline:

8×8 block partitioning

DCT transformation

Quantization using standard luminance quantization table

Zigzag reordering

Inverse quantization and IDCT reconstruction

Implement K-Means clustering from scratch - Build the complete iterative algorithm:

Random centroid initialization

Distance calculation and assignment

Centroid update (mean of cluster points)

Convergence detection

Build an interactive GUI - Allow users to experiment with compression and clustering parameters

🛠️ Libraries Used
Library	Purpose
tkinter	GUI creation (file dialogs, buttons, input fields)
PIL (Pillow)	Image loading, resizing, and format conversion
numpy	Matrix operations, array manipulations
matplotlib	(Imported for potential visualizations)
scipy.ndimage	(Imported for additional processing)

This project was developed as a Master's Lab project in Computer Vision focusing on two fundamental image processing techniques implemented entirely from scratch:

Discrete Cosine Transform (DCT) - A lossy image compression algorithm (similar to JPEG) that transforms images from spatial to frequency domain

K-Means Clustering - An unsupervised segmentation algorithm that partitions images into K distinct regions based on pixel intensity

The project features an interactive Tkinter GUI allowing users to upload images, adjust parameters (number of clusters, cluster selection), and visualize compression and segmentation results in real-time.

🎯 Project Objectives
Understand DCT-based compression - Master the mathematics of frequency domain transformation and quantization

Implement DCT/IDCT from scratch - Build 2D Discrete Cosine Transform without using library implementations

Implement JPEG-style compression pipeline:

8×8 block partitioning

DCT transformation

Quantization using standard luminance quantization table

Zigzag reordering

Inverse quantization and IDCT reconstruction

Implement K-Means clustering from scratch - Build the complete iterative algorithm:

Random centroid initialization

Distance calculation and assignment

Centroid update (mean of cluster points)

Convergence detection

Build an interactive GUI - Allow users to experiment with compression and clustering parameters

🛠️ Libraries Used
Library	Purpose
tkinter	GUI creation (file dialogs, buttons, input fields)
PIL (Pillow)	Image loading, resizing, and format conversion
numpy	Matrix operations, array manipulations
matplotlib	(Imported for potential visualizations)
scipy.ndimage	(Imported for additional processing)

📈 Example Parameters
Algorithm	Recommended Values
DCT	Fixed 8×8 blocks, standard quantization table
K-Means	K = 2-10, cluster to show = 0 (or any)
K-Means Segmentation Examples:

K=2 → Foreground/background separation

K=3-5 → Multi-region segmentation

K=8-10 → Detailed region separation (may over-segment)
