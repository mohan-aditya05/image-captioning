# A new technique for Image Captioning based on Hierarchical Clustering, K-means Clustering and Deep Learning
Image captioning is the task of generating a caption for an image. We explore new models and analyse their performances. One of the key challenges of image captioning is that the model should be able to determine the relationship between the subjects and describe the scene accurately. This has been accompalished using encoder-decoder models where we extract features from images using a CNN architecture and train a language model which generates a caption word by word. We seek to make this process more efficient and accurate using clustering techniques. 

In most of the previous works the models were found to be excessively data-hungry and time consuming to train. We seek to solve this using clustering techniques. We followed two approaches:

## Flow Diagram

![Image of flow](https://github.com/mohan-aditya05/image-captioning/blob/master/Flow%20diagram.png)

## Clustering on images

We perform hierarchical agglomerative clustering on features extracted from images. 
