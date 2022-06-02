# majorChess
major chess

This is used for modelling the chess piece detection for the Major Project of Group 11.

An explanation of the dataset is shown as follows:
1. Dataset has 3 parts: test, valid (val), train
2. Each part contains images and labels with the format of COCO (.txt).
3. The coco.yaml file is the way to call each part of the dataset for modelling. It contains 12 classes of chess pieces
4. We applied the datase in Colab. 
5. The images has 7 data augmentation method: gauss, salt&pepper, possion, saturation with hsv, saturation with hsl, contrast, and speckle
