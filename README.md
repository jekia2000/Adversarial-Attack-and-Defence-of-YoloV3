# Adversarial-Attack-and-Defence-of-YoloV3
This project was my Bachelor's Thesis. It consists of developing an adversarial attack and defense against it on YoloV3, as well as some benchmarking. The project was developed on Linux, but can easily be used on Windows by changing the pickle import libabry and converting bash files into batch files. The instructions for Linux are given in the Guidelines. More about the project and yielded results can be read in the Final Report.
Special thanks and credits to the authors of components used in the project:
1) YoloV3: https://github.com/ultralytics/yolov3
2) YoloV5: https://github.com/ultralytics/yolov5
3) Daedalus: https://github.com/NeuralSec/Daedalus-attack
4) Feature Space attack: https://github.com/qiulingxu/FeatureSpaceAttack
5) Patch atack: https://github.com/UMBCvision/Contextual-Adversarial-Patches
6) Feature alignment defence: https://github.com/grispeut/Feature-Alignment

As the space of a Github free account is limited, here are the weights/folders you need to download:
1) yolov5 weights: https://kuleuven-my.sharepoint.com/:u:/g/personal/aleksa_jelaca_student_kuleuven_be/EQe8esPmuBBPn3yBEjj8_PIBugpERyJQ8jJwxsm_i5rRcA?e=JwAYQO go into the folder  ./yolov5
2) yolov3 weights: https://kuleuven-my.sharepoint.com/:u:/g/personal/aleksa_jelaca_student_kuleuven_be/EaLnwqrsxvJChCyvk8blrFoB5x1TGp03RPNRCu97Ph_aSQ?e=DVEShs go into the folder ./yolov3
3) folder "converted weights": https://kuleuven-my.sharepoint.com/:f:/g/personal/aleksa_jelaca_student_kuleuven_be/EuQR_RC7pFJOj-i5i8Xz0hsBUafu0REvgJBvlWBYGEqZKA?e=I8G1gS  goes into ./yolov3/PFSA/
4) folder "runs": https://kuleuven-my.sharepoint.com/:f:/g/personal/aleksa_jelaca_student_kuleuven_be/Emo4HMciZbNDu1U78DOooH4BoXNSpJiDdZxz_J6ATCUV0g?e=9LZZMD goes into ./yolov3
5) folder "public_directorium": https://kuleuven-my.sharepoint.com/:f:/g/personal/aleksa_jelaca_student_kuleuven_be/EuDLHFKfV1NBjAtWO51fXKoBzyDC75hh8nhaC1fDU5YeFA?e=4fLZZ1 goes into ./
6) vgg19 weights: https://kuleuven-my.sharepoint.com/:u:/g/personal/aleksa_jelaca_student_kuleuven_be/EbiAIvT-PwlBrngRfqD7BHsB6iW0fW4nKJPKPjX-kvX6-A?e=UYrfWm go into ./yolov3/PFSA


