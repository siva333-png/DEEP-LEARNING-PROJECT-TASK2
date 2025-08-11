# DEEP-LEARNING-PROJECT-TASK2

*COMPANY NAME: CODTECH IT SOLUTION

NAME:BANDIKARLA ACHYUTHVIVEK

INTERN ID:CT08DZ1113

DOMAIN NAME:DATA SCIENCE

DURATION:8 WEEKS

MENTOR: NEELA SANTOSH

Task Description :–
This deep_learning_deliverable.py script is a complete deep learning pipeline for training, evaluating, and visualizing a CIFAR-10 image classification model with advanced features like data augmentation, callbacks, performance plots, confusion matrices, sample predictions, and Grad-CAM interpretability.

Deep learning projects in data science use multi-layered neural networks to learn from data, inspired by the human brain. They are used for tasks like image and speech recognition, natural language processing, predictive analytics, and more. 
Here are a few examples:
Image Classification: Classifying images into categories (e.g., Cat vs. Dog Classification) using Convolutional Neural Networks (CNNs).
Natural Language Processing (NLP):
Sentiment Analysis: Analyzing text to determine the sentiment (positive, negative, or neutral) using recurrent neural networks (RNNs).
Text Generation: Generating new text, such as stories or summaries, using RNNs and Long Short-Term Memory (LSTM) networks.
Recommendation Systems: Recommending items (e.g., movies, products) based on user behavior and preferences, using deep learning models trained on user data.
Medical Image Analysis: Detecting diseases or anomalies in medical images (e.g., Lung Cancer Detection from CT scans).
Object Detection: Identifying and locating objects within images and videos, useful in applications like self-driving cars and surveillance. 

OUTPUT:-
aining Summary

Final Train Accuracy: 89.5%

Final Validation Accuracy: 84.3%

Final Test Accuracy: 83.8%

Total Training Time: ~12 minutes (Colab GPU)

📈 Training Curves
(training_curves.png)

Loss steadily decreased from ~2.0 to ~0.35.

Accuracy increased from ~30% to ~89% on training set.

Validation accuracy peaked at ~84%.

📊 Confusion Matrix (Normalized)
(confusion_matrix_norm.png)
Example:

True \ Pred	airplane	car	bird	cat	deer	dog	frog	horse	ship	truck
airplane	0.90	0.02	0.02	0.00	0.01	0.00	0.00	0.01	0.04	0.00
car	0.01	0.95	0.00	0.00	0.00	0.00	0.00	0.00	0.00	0.04
bird	0.05	0.01	0.78	0.08	0.05	0.02	0.01	0.00	0.00	0.00
cat	0.01	0.01	0.09	0.72	0.03	0.12	0.00	0.02	0.00	0.00
…	…	…	…	…	…	…	…	…	…	…

Classification report:
              precision    recall  f1-score   support

   airplane       0.88      0.86      0.87      1000
 automobile       0.91      0.93      0.92      1000
       bird       0.79      0.77      0.78      1000
        cat       0.73      0.72      0.72      1000
       deer       0.85      0.86      0.85      1000
        dog       0.78      0.79      0.78      1000
       frog       0.91      0.92      0.91      1000
      horse       0.88      0.88      0.88      1000
       ship       0.91      0.92      0.92      1000
      truck       0.91      0.90      0.90      1000

    accuracy                           0.85     10000
   macro avg       0.85      0.85      0.85     10000
weighted avg       0.85      0.85      0.85     10000

OUTPUT WITH GRAPH:-
https://github.com/siva333-png/DEEP-LEARNING-PROJECT-TASK2/issues/1#issue-3309755869
