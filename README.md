**BRAIN_MRI_Tumor_Classification**
The work involves building and training a convolutional neural network (CNN) model for classifying brain MRI images into four categories: 'pituitary_tumor', 'meningioma_tumor', 'glioma_tumor', and 'normal'. The dataset is located at /kaggle/input/brain-mri-images-dataset/mri, with each image resized to 128x128 pixels and consisting of three color channels (RGB), resulting in an input shape of (21672, 128, 128, 3). The CNN architecture includes several convolutional layers followed by max-pooling and dropout for regularization, designed to identify patterns specific to each category. The model's performance is evaluated using metrics such as the ROC curve and confusion matrix, with training and validation accuracy and loss visualized across epochs. Data augmentation is used to enhance the model's ability to generalize, and the training history is plotted to track the model's progression during training.

![image](https://github.com/user-attachments/assets/9158235a-c1c7-451f-a5c8-1e1a668b5eb3)


![image](https://github.com/user-attachments/assets/55193cf4-513b-4b10-87ff-d5818a0195be)


![image](https://github.com/user-attachments/assets/c1a6e282-99f7-4b2b-8012-cb8a91f853e0)

![image](https://github.com/user-attachments/assets/b3c67c58-bc1e-4c2f-8d85-f73fd412b13f)

![image](https://github.com/user-attachments/assets/acf841ae-bd25-44ef-9a6d-1ae03228a7b6)


