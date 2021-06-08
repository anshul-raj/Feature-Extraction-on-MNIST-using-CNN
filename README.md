# Feature Extraction on MNIST using-CNN
CNN for Foreground Detection,Circlization and Image segmentation on MNIST dataset

This notebook contains 3 parts

Part 1 : Building a model for foreground extraction trained segmentation masks from TSS algorithm. 

![image](https://user-images.githubusercontent.com/53338289/121176795-425eb380-c87a-11eb-880f-2b5269eff4dd.png)
Original

![image](https://user-images.githubusercontent.com/53338289/121176815-4b4f8500-c87a-11eb-8819-95a3d882ea22.png)
Foreground mask

Part 2 : CNN for locating minimum enclosing circle around the foreground mask obtained from part 1.

![image](https://user-images.githubusercontent.com/53338289/121176903-65896300-c87a-11eb-9c47-888d38a7dae5.png)
Foreground mask

![image](https://user-images.githubusercontent.com/53338289/121176946-720dbb80-c87a-11eb-86c6-3f0a21e528d3.png)
Circlization around the mask

Part 3 : Creating new images by radomly concatinating 4 images in a 2x2 format and then training a CNN to perform image segmentation into 11 classes ( 1 background + 10 numbers )

![image](https://user-images.githubusercontent.com/53338289/121177016-8651b880-c87a-11eb-94a6-d6efeb86c505.png)

Concatinated image
