# Building a CNN for Image Classification-CIFAR10
  
  This model has been implemented on convultional network using three convolutional layer and predicts
  vechiles,animals,birds,reptiles by their name i.e;
  * Airplane
  * Automobile
  * Cat
  * deer
  * dog
  * frog
  * horse
  * Ship

## Library Used
   
   * Numpy
   * Matplotlib
   * Keras
   * Opencv
   '''
    pip install Numpy
    pip install keras
    pip install matplotlib
    pip install python-opencv
   '''    

## Convolutional Neural Network
   
   Training dataset shape-(50000,32,32,3)
   Test Dataset shape-(10000,32,32,3)
   
   * Used two convolutional layer having features of 32 in first layer and 64 in second layer.
   * Kernel Size used in convolutional layer is (3,3)
   * Maxpooling having kernel_size (2,2)
   * Dropout layer 0.25 in first layer and 0.5 in second layer.

## Architecture
   ![img-alt]("https://github.com/Raushan998/CIFAR-10-MODEL/blob/master/CIFAR10.png")

## Accuracy
   * Test Loss-0.94166
   * Test accuracy-0.6744 
   

