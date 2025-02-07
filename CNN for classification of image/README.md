# CNN for Image Classification (CIFAR-10)

This project involves implementing a basic **Convolutional Neural Network (CNN)** for **image classification** using the **CIFAR-10 dataset**. CIFAR-10 is a widely-used dataset consisting of **60,000 color images** in **10 classes** (e.g., airplanes, cars, animals). The goal is to design a CNN architecture that can classify these images with reasonable accuracy.

## Dataset

The dataset used is **CIFAR-10**, which contains 60,000 32x32 color images across 10 different classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Objective

The primary objective of this project is to implement a simple CNN that can classify the CIFAR-10 images. The project serves as an introduction to key deep learning concepts such as **convolutional layers**, **pooling layers**, **activation functions**, and **training techniques**.

## Techniques Used

- **Convolutional Layers**: Used to extract important features from the images.
- **Pooling Layers**: Max pooling to reduce the image size and improve efficiency.
- **Activation Functions**: LeakyReLU to avoid vanishing gradients and improve model performance.
- **Batch Size Optimization**: To find the best batch size for training.
- **Learning Rate Scheduler**: Used to dynamically adjust the learning rate during training.
- **Regularization**: Dropout layers to combat overfitting.

## Results

After experimenting with different configurations, the best performance (accuracy of **75.8%**) was achieved with the model that included:
- Increased number of **convolutional layers**
- Optimized **batch size**
- Use of **LeakyReLU** activation function
- A **learning rate scheduler** to optimize training efficiency.

Other changes, such as adding extra **dense layers** or switching the optimizer to **RMSprop**, resulted in **reduced performance**. The base model had **overfitting** issues, which were addressed through dropout and regularization techniques.

## Conclusion

In summary, focusing on enhancing the **convolutional layers**, optimizing the **training parameters** (batch size and learning rate), and utilizing **LeakyReLU** yielded the best results. This configuration was the most effective for image classification on CIFAR-10. However, further experiments with more advanced techniques, such as **data augmentation** and **transfer learning**, could provide additional improvements.

## Next Steps

- **Model Enhancement**: Try adding more convolutional and pooling layers to see if the performance can be improved.
- **Hyperparameter Tuning**: Use tools like **Grid Search** to optimize the learning rate and batch size.
- **Advanced Regularization**: Explore techniques like **L2 regularization** or **data augmentation** to reduce overfitting.
- **Transfer Learning**: Consider using pre-trained models like **VGG16** or **ResNet** to improve performance.

## Notebook

You can find the notebook for this project here: [CNN_for_Classification.ipynb](CNN_for_Classification.ipynb)

