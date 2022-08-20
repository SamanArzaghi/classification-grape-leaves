<img src="./img/pre-process.png" align="right" />

# classification-grape-leaves
Using a data set including five types of grape leaves (100 unique photos of each type) and deep learning, we are trying to build a model to perform this classification well.

With simple convolutional neural network we would not achive high accuracy, so we done below steps to improve our accuracy(you can check the complete details in report.pdf).

* Used transfer learning(use pretrained MobileNetV2)
* Used augmentation to increase data size
* Used fooly connected net as classification part
* Used SVM as  classification part(for better result)

# Data set
You can get the dataset with the following link: https://www.muratkoklu.com/datasets/Grapevine_Leaves_Image_Dataset.zip

# Libraries

The main librarie that i use for neural networks is TensorFlow,


<img src="./img/ten.png" />

also i tried the transfer learning with PyTorch to try somthing different(why not?),

<img src="./img/py.png" />

and for the SVM part i used ScikitLearn.

<img src="./img/sc.png"  />


# Report
Also there is a report as PDF that you can follow the code with more details.


# Contact
Created by samanarzaghi@ut.ac.ir / arzaghi.sam@gmail.com - feel free to contact me!
