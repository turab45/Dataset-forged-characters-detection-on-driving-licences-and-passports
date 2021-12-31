
# Dataset: forged characters detection on Driving Licences and Passports

Forged characters detection from personal documents i.e. passport or driving licence is an extremely important and challenging task in digital image forensics, as forged information on personal documents can be used for fraud purposes i.e. theft, robbery etc. For any detection task i.e. forged character detection, deep learning models are data hungry and getting the forged characters dataset for personal documents is very difficult due to various reasons, including information privacy, unlabeled data or existing work is evaluated on private datasets with limited access and getting data labelled is another big challenge. To address these issues, we propose a new algorithm that generates two new datasets named forged characters detection on passport (FCD-P) and forged characters detection on driving licence (FCD-D). To the best of our knowledge, we are the first to release these datasets. The proposed algorithm first reads the plain image, then performs forging tasks i.e. randomly changes the position of the random character or randomly adds little noise or randomly changes the colour of the character. At the same time, the algorithm also records the bounding boxes of the forged characters. To meet real world situations, we perform multiple data augmentation on cards very carefully. Overall, each dataset consists of 15000 images.  Our algorithm code and dataset are publicly available at code and dataset respectively. 


## Algorithm Architecture

![App Screenshot](https://github.com/turab45/Dataset-forged-characters-detection-on-driving-licences-and-passports/blob/master/arch.PNG?raw=true)

