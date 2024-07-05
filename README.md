 # Image Segmentation using K-Means Clustering

This project demonstrates image segmentation using K-Means clustering. The code resizes the input images, applies K-Means clustering to segment the images into different regions, and computes the silhouette score to evaluate the quality of the clusters.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [References](#references)

## Introduction

Image segmentation is the process of partitioning an image into multiple segments or clusters to simplify or change the representation of an image into something more meaningful and easier to analyze. In this project, we use the K-Means clustering algorithm to achieve image segmentation. The K-Means algorithm partitions the image pixels into `k` clusters based on their color similarity.

## Installation

To run this project, you need to have Python installed along with the following libraries:

- numpy
- opencv-python
- scikit-learn
- matplotlib

You can install these dependencies using pip:

```bash
pip install numpy opencv-python scikit-learn matplotlib
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/image-segmentation-kmeans.git
    cd image-segmentation-kmeans
    ```

2. Place your images in a directory, e.g., `images/`.

3. Update the `image_paths` list in the script with the paths to your images:
    ```python
    image_paths = ["images/image1.jpg", "images/image2.jpg"]
    ```

4. Run the script:
    ```bash
    python segment_images.py
    ```

## Results

The script will output the original and clustered images side by side, along with the silhouette score for each clustered image. The silhouette score indicates how well each pixel has been clustered.

### Example Output

1. ![download](https://github.com/adarsh98261/Image-segmentation-using-K-Means/assets/142342806/965a7707-00c6-45a3-97ed-61ed3fa536ab)
2. ![download (1)](https://github.com/adarsh98261/Image-segmentation-using-K-Means/assets/142342806/dd661efc-528d-42fb-aced-15fee5773f5b)
3. ![download (2)](https://github.com/adarsh98261/Image-segmentation-using-K-Means/assets/142342806/98464b20-bd1e-420f-8ea7-4f18f3fa75ca)


## References

- [K-Means Clustering](https://en.wikipedia.org/wiki/K-means_clustering)
- [Silhouette Score](https://en.wikipedia.org/wiki/Silhouette_(clustering))
