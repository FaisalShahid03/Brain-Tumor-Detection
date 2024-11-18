MRI Tumor Classification using VGG-16
This project aims to classify MRI scans to determine if the subject has a tumor or not, using a Convolutional Neural Network (CNN) based on the VGG-16 architecture.

📌 Overview
MRI scans are analyzed to detect the presence of tumors through a binary classification approach. Pre-trained weights of the VGG-16 model were used to leverage transfer learning for this task. The model was fine-tuned to suit the binary classification problem.

📈 Evaluation Metric
The performance of the model is evaluated using Accuracy, defined as:

Accuracy
=
Number of correctly predicted images
Total number of tested images
×
100
%
Accuracy= 
Total number of tested images
Number of correctly predicted images
​
 ×100%
💡 Final Results
Dataset	Accuracy
Validation Set	~88%
Test Set	~80%
⚙️ Model Details
Architecture: VGG-16
Approach: Transfer Learning with fine-tuning
Feel free to explore the code and replicate the results! 😊

