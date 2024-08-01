### Yoga Pose Recognition Using Deep Learning

This repository contains an implementation of a deep learning approach for recognizing Yoga poses in complex real-world environments. Traditional techniques often rely on sophisticated handcrafted features and controlled environments, which limits their practical applicability. Our approach leverages a computationally efficient 3D convolutional neural network (3D CNN) to recognize Yoga poses in real-time, using deep learning methods. This repository aims to provide a robust solution for Yoga pose recognition, promoting further study and application in real-world scenarios.
Link to paper: https://link.springer.com/article/10.1007/s00521-020-05405-5

#### Key Features:
- **Dataset**: A newly created Yoga pose dataset with videos from 27 individuals (8 males, 19 females) performing ten different Yoga poses: Malasana, Ananda Balasana, Janu Sirsasana, Anjaneyasana, Tadasana, Kumbhakasana, Hasta Uttanasana, Paschimottanasana, Uttanasana, and Dandasana. Videos were captured using smartphone cameras with 4K resolution at 30 fps.
- **Architecture**: A modified version of the C3D architecture, optimized for efficiency by pruning fully connected layers and incorporating batch normalization and average pooling layers.
- **Performance**: Achieved a test recognition accuracy of 91.15% on the in-house Yoga pose dataset and 99.39% on a publicly available dataset, with significant improvements in execution speed over existing techniques.
- **Availability**: The in-house created Yoga pose dataset will be made publicly available for further research and development.

### Neural Network Architecture:
![image](https://github.com/user-attachments/assets/d198fb4c-c292-4270-b7fa-7af4ada72d60)

### Model Accuracy:
![image](https://github.com/user-attachments/assets/1deed9fd-7187-4625-b8a7-a58b18e99ad4)
