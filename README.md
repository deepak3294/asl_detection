94% accuracy

-To download the dataset - 
click on this link to jump onto the dataset - https://www.kaggle.com/datasets/deepakladwal/real-time-american-sign-language-asl-detection

1) first click on create_dataset.ipynb file(optional)-
   if you want  to create your own dataset than run this file each click on "c" it captures your sign, after each processing it print that dataset is completely builds.

2) second run preprocessing.ipynb file-
   in this you see your various alphabets each  make an class in which varius images of each class already created.

3) run cnn_model.ipynb file-
   after preprocessing the file is saved into asl_dataset.npz and in cnn_model training of the data occurs. running various epoch and showing graph of accuracy and loss., it saves the model into asl_cnn_model.h5

5) run sign_detector.ipynb file-
   in this your training of dataset is already completes, and when this file run it automatically opens your pc/laptop webcam, now you have to manually check the sign by using the input gestures in an dataset, if it fails than try again and check your dataset how images captures if it not fit and fine run create_dataset.ipynb file again to capture again your sign, and it detect completely.

6) run evaluation.pynb file -
   this file is used to check the final accuracy your model or project build up. this detect the given gestures and compares to the training dataset and build prediction for an 4 second, after each alphabet completes at final it gives the output overall accuracy your model hits.


#you can see my result of prediction in demo.png file

author - deepak3294
license - MIT license
