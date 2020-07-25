# Traffic-Signs-Recognition
Recognizing 43 types of Traffic Signs with CNNs using Keras

The tools used for the code are:
1. Numpy
2. Pandas
3. cv2 (Computer Vision Library)
4. Keras API

The code can be divided as follows:
1. Loading a bucketlist dataset on traffic signs

2. Preprocessing the data:
   Some of the steps used are: 
   
       a) Converting to gray scale,
       
       b) Normalising, as it will improve the computation,
       
       c) Data Augmentation, because we have less data and many classes, we need to create more images or else it may lead to Overfitting
       
3. Creating the Model:

       a) Used a Sequential Model
       
       b) The structure is:
          2 CNNS Layer -> Max Pooling Layer -> 2 CNNs Layer -> Max Pooling Layer -> Flatten -> 2 Dense Layer -> Output
          
       c) Compile the Model
       
4. Evaluating the results

       a) Plotting a Loss Curve for Training and Validation set, to check if overfitting is occuring
       
5. Predicting for an internet image

       a) Loading any image from internet
       
       b) Processesing the image
       
       c) Predicting the class
 
The code will give an accuracy of above 97% on test images! Try varying the hyperparameters like Learning Rate, layers and neurons of the model, or the kernel size of the CNNs or Max Pooling Layer for better accuracy.

Thank you!!
