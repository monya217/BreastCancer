# Advancing Breast Cancer Segmentation: An Ensemble Learning Approach

Project overview
This project delves into the improvement of breast cancer image segmentation through a multi-step approach that includes data preprocessing, classification, and ensemble-based segmentation.The initial dataset underwent preprocessing to ensure it was well-prepared for subsequent stages.Using the VGG model, the preprocessed dataset was classified into tumorous and non-tumorous images, resulting in a new dataset which was then subjected to segmentation. 

Five distinct segmentation models—UNet, Attention UNet, Residual UNet, SegNet, and DeepLab—were individually assessed, with DeepLab demonstrating the highest individual performance at an IoU Dice Balance of 0.865 and SegNet recording the lowest at 0.436.

The basis of the study is centred on the use of ensemble learning to merge multiple segmentation models. Through the employment of threshold voting, significant improvements in segmentation results were observed. DeepLab and Attention UNet combined to form the most effective ensemble combination, with Mean IOU of 0.876 and Mean dice coefficient of 0.932 and thus an IOU Dice Balance of 0.904 at a threshold of 0.9.


About Dataset
The data reviews the medical images of breast cancer using ultrasound scan.Breast Ultrasound Dataset is categorized into three classes: normal, benign, and malignant images. Breast ultrasound images can produce great results in classification, detection, and segmentation of breast cancer when combined with machine learning.

The data collected at baseline include breast ultrasound images among women in ages between 25 and 75 years old. This data was collected in 2018. The number of patients is 600 female patients. The dataset consists of 780 images with an average image size of 500*500 pixels. The images are in PNG format. The ground truth images are presented with original images. The images are categorized into three classes, which are normal, benign, and malignant.
Team Details

Manasvi Jindal (AIML)

Monya Mehta (AIML)
