### Yoga Pose Recognition Using Deep Learning

This repository contains an implementation of a deep learning approach for recognizing Yoga poses in complex real-world environments. Traditional techniques often rely on sophisticated handcrafted features and controlled environments, which limits their practical applicability. Our approach leverages a computationally efficient 3D convolutional neural network (3D CNN) to recognize Yoga poses in real-time, using deep learning methods.

#### Key Features:
- **Dataset**: A newly created Yoga pose dataset with videos from 27 individuals (8 males, 19 females) performing ten different Yoga poses: Malasana, Ananda Balasana, Janu Sirsasana, Anjaneyasana, Tadasana, Kumbhakasana, Hasta Uttanasana, Paschimottanasana, Uttanasana, and Dandasana. Videos were captured using smartphone cameras with 4K resolution at 30 fps.
- **Architecture**: A modified version of the C3D architecture, optimized for efficiency by pruning fully connected layers and incorporating batch normalization and average pooling layers.
- **Performance**: Achieved a test recognition accuracy of 91.15% on the in-house Yoga pose dataset and 99.39% on a publicly available dataset, with significant improvements in execution speed over existing techniques.
- **Availability**: The in-house created Yoga pose dataset will be made publicly available for further research and development.

This repository aims to provide a robust solution for Yoga pose recognition, promoting further study and application in real-world scenarios.
