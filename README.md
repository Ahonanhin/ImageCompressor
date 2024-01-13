# K-Means Image Compression

This repository contains a Python script that uses K-means clustering to compress images.

## Dependencies

The script depends on the following Python libraries:

- numpy
- cv2 (OpenCV)
- os
- matplotlib
- sklearn

You can install these with pip:
pip install numpy opencv-python os matplotlib scikit-learn


## Usage
The main function in the script is kmeans_image_compression(image_path, num_clusters), which takes an image path and the number of clusters for K-means as input, and outputs a compressed version of the image.

The script also contains a kmeans_numpy(X, n_clusters, max_iters=100) function, which implements the K-means algorithm using numpy.

Here is an example of how to use the script:

image_path = "test_image.png"
num_clusters = 10  # Adjust the number of clusters as needed
kmeans_image_compression(image_path, num_clusters)
You can also test with different numbers of clusters:

num_clusters = 2
kmeans_image_compression(image_path, num_clusters)
num_clusters = 5

The script will output the original and compressed images, as well as the compression ratio. The compressed image will be saved as compressed_image.png.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
