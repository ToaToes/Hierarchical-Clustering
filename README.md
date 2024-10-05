# Hierarchical-Clustering
<br />This is an implementation of generic Hierarchical Clustering Algorithm as described
<br />in this webpage:
```
http://home.dei.polimi.it/matteucc/Clustering/tutorial_html/hierarchical.html
```
<br />This is a Hierarchical Clustering with a constant "threshold" that indicate
<br />the maximal distance between two clusters to group them. The algorithm stops
<br />when no cluster can be merged. 
<br />The distance between two clusters is calculated as the distance between the
<br />medians of the two clusters.

<br />refer to:
```
http://mirlab.org/jang/books/dcpr/dcHierClustering.asp?title=3-2%20Hierarchical%20Clustering%20(%B6%A5%BCh%A6%A1%A4%C0%B8s%AAk)
```


<br />Data Exploration: Understanding the dataset by clustering similar images can help in analyzing diversity and common features.
<br />Data Selection: If you have a large dataset, you can use clustering to select representative images from each cluster for training, thus reducing the size of the dataset while maintaining diversity.
<br />Feature Extraction: You can cluster images based on feature representations from a pre-trained model (like a convolutional neural network), which can help identify similarities among images.
