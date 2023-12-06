# Mini-Project-Readme-File
Title of the Project : LUNG NODULE DETECTION USING DEEP LEARNING TECHNIQUES
Project Idea :
To develop a system that detects lung nodules in CT Scan images from the LUNA16 dataset, evaluating whether it is benign or malignant.
Modules included in our Project:
1) Image Preprocessing
2) Feature Extraction
3) Model Training
4) Model Evaluation
   
**Image Preprocessing**:
Data preprocessing is the process of preparing and transforming raw data to make it suitable for analysis and modeling tasks.
Here, the input images are resized, normalized,transformed into a suitable format (numpy arrays) for further model training.
This step is crucial in ensuring that the input data is standardized, informative and suitable for feeding into the model.

**Feature Extraction**:
Feature extraction is done using CNN which helps in capturing relevant and discriminative features from images.
These CNNs consist of multiple convolutional and pooling layers that automatically learn hierarchical representations or features from the input images.
The network architecture uses successive convolutional layers to extract various complex patterns, shapes, and structures present in the lung X-ray images, thereby capturing relevant features for nodule detection and classification.
It leverages the learned representations from a large dataset, saving time and resources.
These extracted features can be used as input for the classification task effectively.

**Model Training**:
The process of training a machine learning model on a labeled dataset to learn the underlying patterns and relationships between input features (in this case, extracted image features) and their corresponding target labels (nodule classes).
Built a convolutional neural network (CNN) using TensorFlow and Keras to learn features from the images and detect nodules.

**Model Evaluation**:
The evaluation of nodule detection in CT Scans involves utilizing three key metrics: the Area Under Receiver Operating Characteristic Curve (AUROC), which assesses sample-level performance by analyzing nodule likelihood predictions within individual X-rays; the False Positive Rate at 25% Sensitivity (FROC25%), which evaluates the balance between sensitivity and false-positive predictions at the bounding-box level; and a combined metric that linearly combines AUROC and FROC25% to provide an overall assessment of the model's performance in detecting nodules while considering sensitivity and false-positive rates simultaneously. These metrics collectively offer insights into the model's ability to discern nodules from non-nodules and balance the trade-off between sensitivity and false-positive predictions.

**Conclusion**:
A deep learning model is developed that detects the nodule in CT scans. For better accuracy, the
model is trained with different activation functions and compared.
Among all those ReLu gives highest accuracy.

In Future, the scope entails enhancing the interactive visualization dashboard to incorporate advanced machine learning algorithms for real-time data analysis, facilitating quicker and more accurate correlation discovery between patient factors and cancer attributes. Additionally, expanding the 3D visualization tools to include augmented reality (AR) features can offer a more immersive and accessible patient education platform, further assisting in treatment comprehension and planning for both patients and healthcare professionals.
