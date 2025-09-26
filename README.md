# Multiclass-Image-Classification
This project classifies butterfly images divided into 75 classes. <br>
- In this project I have selected https://www.kaggle.com/datasets/phucthaiv02/butterfly-image-classification dataset from Kaggle platform.<br>
- Dataset has train and test datas, train size is 6499.<br>
- The classes in the dataset are fairly evenly distributed.<br>
- However, each class has only a few samples, so data augmentation was applied.<br>
- Project alson in my Kaggle account here is link : <br>
CNN model was used, also for regulirization dropout layers, batch normalization was added to model.<br>
In data augmentation phase, six sample generated from original images and both train and generated images are used in model training.<br>
SparseCategoricalCrossentropy used for multi-class classification and class names are initially string data type then I have encoded them to integer by using Label Encoder. <br>
activation function is softmax and optimization algorithm is adam which is highly robust and succesful.<br>
### Future Work
Transfer Learning can be used. <br>
I would have used it, but I couldn’t meet the deadline.
