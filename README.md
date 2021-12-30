
# Dataset: forged characters detection on ID cards

Tampered character detection in an identity card (ID card) is an extremely important and challenging task in digital image forensics, as tampered information in an ID card can be used for fraud purposes i.e. theft, robbery etc. For tempered character detection, deep learning models are data hungry and getting the forged card dataset is very difficult due to various reasons, including information privacy, unlabeled data or existing work is evaluated on private datasets with limited access and getting data labelled is another big challenge. To address these issues, we propose a new algorithm that generates a new dataset for tampered character detections for ID cards (TCD-ID) and to the best of our knowledge we are the first to release this dataset. Our algorithm first reads the plain card image, then performs tampering tasks i.e. randomly changes the position of the random character or randomly adds little noise or randomly changes the colour of the character. At the same time, the algorithm also records the bounding boxes of the tampered character. To meet real world situations, we perform multiple data augmentation on cards very carefully. Overall, the dataset consists of 15000 images.  Our algorithm code is publicly available at code link and the dataset available at dataset link.


## Algorithm Architecture

![App Screenshot](https://github.com/turab45/Dataset-forged-characters-detection-on-ID-cards/blob/master/arch.jpg?raw=true)

