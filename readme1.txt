Vegetable Classification using Teachable Machine
This project demonstrates a vegetable classification model created using Teachable Machine. The model is trained to classify vegetables like Beans and Tomatoes using a dataset of images, and it provides predictions with high confidence through webcam or file input.

Features
Image Classification: Accurately predicts vegetable types such as Beans and Tomatoes.
Custom Dataset: Includes 1000+ images per class for robust training.
Training Parameters:
Epochs: 50
Batch Size: 16
Learning Rate: 0.001
Live Testing: Supports webcam and file uploads for real-time predictions.
Model Export: Easily export the trained model for integration into other systems.
Dataset
The dataset consists of:

Beans: 1000+ image samples
Tomatoes: 1000+ image samples
Each image is used to train the model for reliable classification.
How It Works
Dataset Upload: Images are uploaded to Teachable Machine under separate categories.
Training: The model is trained using the following parameters:
Epochs: 50
Batch Size: 16
Learning Rate: 0.001
Prediction: Test the model with live webcam input or by uploading an image.
Output: The model predicts the vegetable class with a confidence percentage.
Usage
Live Testing
Use webcam input or upload an image through the testing panel.
The predicted class and confidence percentage will be displayed.
Exporting the Model
After training, export the model to use in external applications. Supported formats include TensorFlow, Keras, and others.
Example Output
Input Image	Predicted Class	Confidence
Beans	Beans	100%
Tomato	Tomato	98%
Installation & Setup
Clone this repository:
bash
Copy
Edit
git clone https://github.com/yourusername/vegetable-classification  
cd vegetable-classification  
Train your model using Teachable Machine and export it.
Integrate the exported model into your application for real-time classification.
Tools & Technologies Used
Teachable Machine: For model training and testing.
Machine Learning: Image-based classification.
Contributing
Contributions are welcome! Feel free to fork the repository, submit issues, or create pull requests.

License
This project is licensed under the MIT License. See the LICENSE file for more details.