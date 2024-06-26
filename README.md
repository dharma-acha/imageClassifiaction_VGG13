## CNN Classification with VGG-13

### VGG-13 Implementation
In this part of the project, we implement the VGG-13 (Version B) architecture to solve an image classification problem with three classes: dogs, cars, and food. The dataset contains 10,000 examples for each category, totaling 30,000 samples, each being a 64x64 image. The expected accuracy is over 75% without optimization techniques and 80% with optimization techniques.

### Project Steps
#### Data Preprocessing:

Read, preprocess, and print main statistics about the dataset.
Visualize the dataset using libraries like matplotlib, seaborn, or plotly.
Normalize the data, convert targets to categorical values, and split the dataset into training, validation, and testing sets.

#### VGG-13 Implementation:

Implement the VGG-13 architecture using the specified kernel sizes, strides, and padding from the original VGG paper.

#### Model Training:

Train the VGG-13 model on the provided dataset, adjusting the input and output layers as necessary.

#### Overfitting Prevention and Optimization:

Apply regularization (L1/L2), dropout, early stopping, and image augmentation to improve model performance and prevent overfitting.


#### Model Saving:

Save the weights of the best-performing model and ensure the functionality of model saving and loading using PyTorch.

#### Results and Visualization:

* Report training accuracy, training loss, validation accuracy, validation loss, testing accuracy, and testing loss.
* Plot training and validation accuracy and loss over epochs.
* Generate a confusion matrix and calculate additional evaluation metrics such as precision, recall, and F1 score.

### Deliverables
* **VGG-13 Model:** Implementation details and training process.
* **Optimization Techniques:** Methods applied to prevent overfitting and improve results.
* **Performance Metrics:** Detailed reporting and visualization of accuracy, loss, and other evaluation metrics.

### Contact

If you have any questions or comments, feel free to contact me on [Email](mailto:achadharma333@gmail.com)

