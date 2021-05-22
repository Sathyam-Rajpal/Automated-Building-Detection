- ABSTRACT

Automatic extraction of buildings from remote sensing imagery is of great significance for many applications, including urban planning, navigation, and disaster management. In recent years there have been many advancements in the field of computer vision which has led to the improvement in the capabilities of remote sensing techniques. As a result, there has been a significant increase in the availability and accessibility of high-resolution remote sensing images. Hence, with the 
increased availability of high-quality data for spatially large areas, it is possible to perform accurate image segmentation targeting the extraction of buildings.
With the recent availability of commercial high-resolution remote sensing multispectral imagery from sensors such as IKONOS and QuickBird, it is possible to identify small scale features such as individual roads and buildings in the urban environment. Imagery from these sensors is an important source of timely data that can be used in a variety of urban area applications. In this paper we propose a transfer-learning based CNN architecture CNN based machine learning architecture to extract the 
footprints of the buildings in a given set of satellite images

- MOTIVATION

Building detection in a remote sensing image is an instance segmentation task. We need to first classify if an object in an image is a building or not 
and then a mask depicting the building boundary is created. Object detection in machine learning using Convolutional Neural Networks (CNN). CNN extract 
high- and low-level details from the images by repeated convolution with several feature maps followed by pooling operations. Since, remote sensing images
carry a lot of spatial information effective extraction of information from these images require very deep CNN’s consisting of many layers of convolution 
and pooling that requires a lot of computation. To deal with the potentially complex texture of buildings in general and image background, the existing 
methods try to perform extensive pooling and striding operations used in CNNs which reduces feature resolution causing a loss of detailed information that 
results in less accurate predictions. A large architecture also means that we need to use much computing power to train the model to get meaningful results.
To address this issue, we intend to build a light-weight deep learning model integrating the ResNet-50 architecture as the encoder which is already been 
trained on ImageNet dataset and finally up-sample the images to the same size to get the final output as binary images.

- MODEL WORKFLOW
                        
     ![image](https://user-images.githubusercontent.com/45162308/119216683-bb2be480-baf2-11eb-8816-118403d5e8dc.png)



- MODEL ARCHITECTURE
             
     ![image](https://user-images.githubusercontent.com/45162308/119216653-8324a180-baf2-11eb-8e25-bad74a4cfd9e.png)

- RESULTS

     ![image](https://user-images.githubusercontent.com/45162308/119216813-840a0300-baf3-11eb-9cca-f4328a680f9e.png)

- COMPARATIVE PERFORMANCE

     ![image](https://user-images.githubusercontent.com/45162308/119216841-a865df80-baf3-11eb-8ae8-31346fc34b54.png)

* Link to the dataset: https://www.cs.toronto.edu/~vmnih/data/
