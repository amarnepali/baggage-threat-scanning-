# baggage-threat-scanning-
It includes the x-ray screening dataset, I am applying object detection method for the detection, segmentation and experimentation of machine learning and deep learning models


Dataset information: https://www.kaggle.com/datasets/muhammadzakria2001/baggage-xray-threats/



baggage-screening-threat-detection.ipynb file includes the experimentation of dummy x-ray dataset created using stable diffusion pipeline with prompt as x-ray image of backpack with gun, knife or scissors, and trained the yolo v5 model. The performance was worst. The several reason includes: image dataset and bounding box fixed at center only, and a image includes single threat object per picture, also trained straight forward with no preprocessing and augmentation.
