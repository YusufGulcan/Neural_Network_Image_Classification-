# Neural_Network_Image_Classification
## Introduction 
This project aims to classify objects on images using a convolutional neural network algorithm. The algortihm is higlhy adept at detecting patterns in images and make predictions. The data can be any two files with different types of images in terms of context, e.g. dogs-cats, cars-trucks, buildings-forest etc. The model is trained by using around 450 images in total. 

![image](https://user-images.githubusercontent.com/105684729/187371682-9e37fa5c-7d3c-47ec-bf66-439bba428283.png)



## Project Break Down

- Data collection and Labeling
 This part is pretty flexible, you can use pictures involving the object you want to classify are acceptable. Labeling is done through grouping the images in different folders.

- Loading and Preprocessing the 
The data is read from a source by the code so python 'Os' library is essential here. The directories are defined and read by a computer vision library.
The data is converted and scaled into an appropriate format and finally batches for training, evaluation and testing are created. Form pipelines for the processing step. 

- Modelling the Neural Network Algorithm 
Decide on the layer types and neuron numbers; create layers and put them in order. Train the model and evaluate the result. Iterate the same process in case an optimization opportunity is seen. Finally, save the model.

![image](https://user-images.githubusercontent.com/105684729/187367921-a323d01b-f424-43d7-b3a4-96f1ed06dbbe.png)
 
### Libraries
- Os , cv2, Keras, Tensorflow, Pandas, NumPy


## Conclusion 

![image](https://user-images.githubusercontent.com/105684729/187371578-004f8baa-cc01-48a3-81b2-5f1b5857620d.png)


The model showed a perfect success rate on validation part. Test data is evaluated with %98 success rate. Although it looks good on paper, it needs be tested more using  bigger data. Overall, it look promising for now. 

I am always open to contributions.

## References 
- [Nicholas Renotte](https://www.youtube.com/c/NicholasRenotte) 
A big thanks to Nicholas Renotte, I learned a lot from him about neural networks. I was inspired by his works.

- [Tensorflow Documentation](https://www.tensorflow.org/api_docs) 
- [OpenCV Documentation](https://docs.opencv.org/4.x/)




