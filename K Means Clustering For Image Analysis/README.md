# Handwritten Digit Recognition with K-Means Clustering 🖋️🔍

## Introduction ℹ️

This project aims to explore handwritten digit recognition using K-Means clustering. Leveraging the MNIST dataset and Python libraries such as NumPy, Matplotlib, and Scikit-learn, we delve into clustering techniques to categorize handwritten digits and analyze their patterns.

## Aim 🎯

The primary goal is to apply K-Means clustering to the MNIST dataset for handwritten digit recognition. By segmenting the dataset into clusters, we aim to gain insights into the similarities and differences among handwritten digits and evaluate the clustering performance.

## Methodologies 📈

- **Data Preprocessing:** Reshaping and normalizing the input data to prepare it for clustering.
- **K-Means Clustering:** Utilizing the MiniBatchKMeans implementation from Scikit-learn for clustering.
- **Evaluation:** Assessing clustering performance using metrics such as inertia, homogeneity, and accuracy.

## Tools and Frameworks 🛠️

- **Python Libraries:** NumPy, Matplotlib, Scikit-learn
- **Deep Learning Framework:** Keras (for loading the MNIST dataset)
- **Visualization:** Matplotlib for displaying handwritten digit images and centroids.

## Description 📝

This project involves loading the MNIST dataset, performing K-Means clustering on the digit images, and visualizing the resulting clusters and centroids. We explore the characteristics of each cluster and evaluate the accuracy of clustering on both training and testing datasets.

## Results 📊

- Identified clusters representing different handwritten digit patterns.
- Evaluated clustering performance using metrics such as inertia and homogeneity.
- Visualized centroids to understand the characteristics of each cluster.

## Future Enhancements 🚀

- Incorporate dimensionality reduction techniques for more efficient clustering.
- Explore alternative clustering algorithms to compare performance.
- Develop a user-friendly interface for interactive exploration of clustered digit images.

## Location of Files 📂

- `handwritten_digit_recognition.py`: Main Python script containing the project code.
- `README.md`: Documentation file (you're reading it!)
- `Dataset`: MNIST dataset used for handwritten digit recognition.

## Example Command 💻

To run the handwritten digit recognition and clustering:

```bash
python handwritten_digit_recognition.py
