# Algorithm_02
Algorithm_02  Assignment #5



1.Model

MODEL 1 : 3 Layers with 1 Convolution layer
Model
model_number == 1:
        model = keras.models.Sequential([
                    keras.layers.Conv2D(32, (3,3), activation = 'relu', input_shape = (28, 28,1)),  # layer 1 
                    keras.layers.MaxPool2D((2,2)),                                                  # layer 2 
                    keras.layers.Flatten(),
                    keras.layers.Dense(10, activation = 'softmax')])                                # layer 3

![tupian0611](https://user-images.githubusercontent.com/80154495/121672789-c87d3300-cae2-11eb-96ea-b280c6fc7734.jpg)
