"# surface_crack_defect" 
Content:

Load Dataset
Visualizing the Dataset
Normalization of image data
Convolutional Neural Network (CNN) Model
Model Training
Accuracy and Loss Graphs
Classification Report
Result

![image](https://github.com/nishant050/surface_crack_defect/assets/110757502/0fbf24ce-4737-466c-b81e-65715fd606f2)

![image](https://github.com/nishant050/surface_crack_defect/assets/110757502/9d6e5dc2-1fac-40a3-9c04-50d4ca3fcc24)

CNN Model
Convolutional neural networks (CNN) are a neural network method that can include multiple arrays created to process 2-dimensional arrays of three color components (Lecun et al., 2010). In images, edges called local features form patterns and these patterns combine into pieces, then pieces form objects (Bengio & Lecun, 1997). These properties are obtained in the convolution layer and these properties are brought into a format that can be semantically combined and processed in the pooling layer.

CNN; It is a type of algorithm that consists of an input, an output, and many hidden layers. The hidden layer includes convolution layer, pooling layer, rectified linear unit layer (ReLu), fully connected layer and classification sections (Lecun et al., 2010).

Convolution layer is used in convolutional neural networks to perform convolution process in multi-dimensional processes. This layer enables the adjustment of the neurons in the image matrix, which is defined as the input called feature map, and enables the learning of the properties.

ReLu fulfills the task of flattening the feature map that emerges after the convolution process. By converting negative values to zero, it produces output between zero and positive infinite values.

Pooling layer performs the size reduction operation by performing the function operation defined as subsampling (Kalchbrenner et al., 2014). In addition, thanks to this layer, excessive memorization is prevented.

Regularization in the training phase in CNN. Data augmentation is an important element for regularization of weights and batch normalization (Srivastava et al., 2014). For this reason, the method called Dropout is used. Its main purpose is to prevent overfitting.

![image](https://github.com/nishant050/surface_crack_defect/assets/110757502/1aa902ad-b383-4d22-9e4e-2f6a80065cbe)![image]

Classification Report
The classification_report function builds a text report showing the main classification metrics.

Precision for each class, it is defined as the ratio of true positives to the sum of true and false positives.

Recall for each class, it is defined as the ratio of true positives to the sum of true positives and false negatives.

F1 scores are lower than accuracy measures as they embed precision and recall into their computation.

Result
As a result, 99% success has been achieved.
The accuracy and loss function can change by changing the learning rates or changing the number of epoch.




