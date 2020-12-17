# Grape-Segmentation
A Machine Learning course final project.In this project, we aim to use instance segmentation to detect the grapes in the vineyards.  
We augmented the [Embrapa Wine Grape Instance Segmentation Dataset](https://github.com/thsant/wgisd) and applyed [Mask R-CNN](https://github.com/matterport/Mask_RCNN) on the augmented dataset to generalize the trained model to get resultful detection on the full-plant grape photos from [Vitis International Variety Catalogue](https://www.vivc.de).

## Running Environment
Make sure:  
- Tensorflow==1.15.2  
- Keras==2.1.6  

## Detection 
Open [detection.ipynb](https://github.com/LesleyDing/Grape-Segmentation/blob/main/detection.ipynb) and run all cells.  
Or, if you have your own grape full plant images, you can change ```IMAGE_DIR``` to your directory and run the code.

## Quick Start to Train the Mask R-CNN on Dataset.
### Data Augmentation
First, clone the wgisd dataset to the current folder by ```git clone https://github.com/thsant/wgisd.git```.   
Then make sure that [data_augmentation.ipynb](https://github.com/LesleyDing/Grape-Segmentation/blob/main/wgisd/data_augmentation.ipynb) is inside wgisd folder.  
Open [data_augmentation.ipynb](http://www.example.com) and run all cells.

### Train and evaluate the model
Open [grapes.ipynb](https://github.com/LesleyDing/Grape-Segmentation/blob/main/grapes.ipynb) and run all cells.
