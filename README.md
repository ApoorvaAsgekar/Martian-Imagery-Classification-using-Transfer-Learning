# Martian-Imagery-Classification-using-Transfer-Learning

This project focuses on identifying frost in Martian terrain using deep learning techniques. The dataset comprises HiRISE images annotated with labels for frost and background tiles.

In the first phase, a three-layer CNN followed by a dense layer is trained using image augmentation techniques and ReLU activation functions. Batch normalization, dropout, L2 regularization, and ADAM optimizer are applied, and model performance is evaluated using precision, recall, and F1 score.

In the second phase, transfer learning is employed using pre-trained models (EfficientNetB0, ResNet50, VGG16). Only the last fully connected layer is trained while freezing the earlier layers. Image augmentation is performed, and ReLU activation functions, softmax layer, batch normalization, dropout, and ADAM optimizer are utilized. Model performance is evaluated similarly to the CNN + MLP approach.

The results of transfer learning are compared with the CNN + MLP model to assess performance differences and determine the most effective approach for identifying frost in Martian terrain.






