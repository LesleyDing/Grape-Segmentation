# Grape-Segmentation
A Machine Learning course final project.In this project, we aim to use instance segmentation to detect the grapes in the vineyards.  
We augmented the [Embrapa Wine Grape Instance Segmentation Dataset](https://github.com/thsant/wgisd) and applyed [Mask R-CNN](https://github.com/matterport/Mask_RCNN) on the augmented dataset to generalize the trained model to get resultful detection on the full-plant grape photos from [Vitis International Variety Catalogue](https://www.vivc.de).

## Running Environment
Make sure:  
- Tensorflow==1.15.2  
- Keras==2.1.6  
- Clone the wgisd dataset to the current folder by ```git clone https://github.com/thsant/wgisd.git```  
- The code of ```mrcnn``` module is already in the directory

## Quick Start
### Use Trained Model to Detect
Open [detection.ipynb](https://github.com/LesleyDing/Grape-Segmentation/blob/main/detection.ipynb) and run all cells.  
Or, if you have your own grape full plant images, you can change ```IMAGE_DIR``` to your directory and run the code.

### Train the Mask R-CNN on Dataset
#### Data Augmentation
First, make sure that [data_augmentation.ipynb](https://github.com/LesleyDing/Grape-Segmentation/blob/main/wgisd/data_augmentation.ipynb) is inside wgisd folder.  
Then open [data_augmentation.ipynb](http://www.example.com) and run all cells.

#### Train and evaluate the model
Open [grapes.ipynb](https://github.com/LesleyDing/Grape-Segmentation/blob/main/grapes.ipynb) and run all cells.
