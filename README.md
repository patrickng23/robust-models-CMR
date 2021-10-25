# robust-models-CMR
This was created as part of assessment for a final year engineering assignment 2021. 

Paths included are relative to my google drive and should be updated indicative to your own directory structure.
Included are the weights for 4 models assessed: Baseline 2D UNet (50/100 epochs), H/V Flip (50/100 epochs), H Flip (50/100 epochs) and SimSiam (50/100 epochs).

https://drive.google.com/drive/folders/134wRcyPTBAUQUXnRXoRI0ibpguupGuDF?usp=sharing

The method for training the baseline models is in baseline2D_Unet.ipynb with the SimSiam implementation seen in SimSiam-M&Ms.ipynb

To use the train-image data generator keras function the path to train images and masks needs to point to a directory with folder named 'train' containing images or masks.


Data used was from the M&Ms challenge 2020 dataset which can be accessed from this link https://www.ub.edu/mnms/. 

V. M. Campello et al., "Multi-Centre, Multi-Vendor and Multi-Disease Cardiac Segmentation: The M&Ms Challenge," in IEEE Transactions on Medical Imaging, doi: 10.1109/TMI.2021.3090082.

The SimSiam implementation was based on Sayak Paul's keras example.

https://keras.io/examples/vision/simsiam/#defining-our-data-augmentation-pipeline
