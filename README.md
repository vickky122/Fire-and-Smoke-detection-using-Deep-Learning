# Fire-Smoke-Detection
Detecting Fire, Smoke using Computer Vision, Open CV and PyTorch

Early fire/smoke detection plays a very important role in protecting many lives also property loss can be reduced and downtime for the operation minimized through early detection. Therefore in this project I have developed an Computer Vision & Deep Learning pipeline for fire and smoke detection.


### Download the Dataset - [download](https://github.com/DeepQuestAI/Fire-Smoke-Dataset/releases/download/v1/FIRE-SMOKE-DATASET.zip)

### Download the documentation - https://drive.google.com/file/d/1_-oAzIICKxIyD3N3_5CAIZYqfy0wbdqZ/view?usp=sharing

### Dataset Folder - 
    Train
        - Fire
        - Neutral
        - Smoke       
    Test
        - Fire
        - Neutral
        - Smoke
        
    Dataset contains 1000 images of each class
    
### Model Structure -
For traing the model I have used transfer learning technique. Architecture used here is ResNet50 which is pretrained on ImageNet dataset.
I have achieved validation accuracy of 93% using ResNet.
For more info about training and graphs - open Training.ipynb



### Requirements - 
Python3

PyTorch

OpenCV

Matplotlib

Numpy


