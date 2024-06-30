# Food-Calorie-Analytics

ABSTRACT : 

Our project aims to present a novel approach to enhancing food calorie analytics by integrating state-of-the-art computer vision models, EfficientNetB3, and YOLOv7. With the growing prevalence of dietaryrelated health concerns, accurately assessing the caloric content of food items has become paramount. Traditional methods often rely on manual
estimation or simplistic algorithms, leading to inaccuracies and inefficiencies. In this project, we propose a sophisticated framework that leverages the capabilities of EfficientNetB3 for feature extraction and image identification, and YOLOv8 for object segmentation. From the information collected through segmentation, the calorie content is calculated, facilitated by the utilization of a CSV file. We demonstrate the effectiveness of our approach through extensive experimentation on diverse food datasets, achieving significant improvements in both accuracy and efficiency compared to existing methods.

MODEL SUMMARY : 

EfficientNetB3 Model : The food image classification model is built upon transfer learning using the EfficientNetB3 architecture, which serves as the backbone for feature extraction. Additional layers, including Batch Normalization, Dense, and Dropout layers, are appended to the base model for further processing. The food image classification model is meticulously designed to tackle the intricate task of categorizing diverse food items into 20 distinct classes. Leveraging transfer learning, the model capitalizes on the EfficientNetB3 architecture, renowned for its efficiency and effectiveness in handling image classification tasks. Augmented with additional layers for finetuning and classification, the model undergoes rigorous training, optimizing its parameters to attain remarkable performance metrics.

YOLOV8 Model : YOLOv8, an evolution in aims to provide state-of-the-art performance in real-time object detection tasks. Its purpose is to accurately identify and localize objects within images or videos swiftly, enabling applications like surveillance, autonomous driving, and augmented reality to operate effectively. YOLOv8 achieves this by leveraging machine learning techniques, particularly deep convolutional neural networks, to make rapid and accurate decisions about the presence, class, and location of
objects in visual data. Through continuous learning and refinement, YOLOv8 enhances its ability to recognize diverse objects across various environments, contributing to advancements in computer vision and enabling innovative solutions across industries.

DATA ACQUISITION : 

The following link consists of the dataset being used:
Link: https://drive.google.com/file/d/1H9hEnBR7hicROM3iKbb6fAW7HC7dP1aX/view?usp=drive_link

The dataset used in the project consists of images of various food items categorized into 20 classes or food categories. Each food category contains approximately 200 images, contributing to a diverse and sizable dataset for training and evaluation purposes. The dataset is organized into directories, with each directory representing a specific food category which facilitates easy access and management of the dataset during preprocessing and model training stages. In the calorie dataset, the calorie contents are mapped to these class labels.

CONCLUSION :

In conclusion, our project represents a significant advancement in the field of food recognition and calorie prediction through image processing techniques. By leveraging state-of-the-art models such as YOLOv8 and EfficientNetB3, we have developed a robust system capable of accurately identifying food items within images and predicting their
calorie content. 

FUTURE SCOPE : 

Looking ahead, there are several avenues for further research and enhancement of our system. One potential direction is the integration of additional nutritional information beyond calorie content, such as macronutrient composition. By incorporating data on protein, carbohydrates, and fats, our system could provide users with even more comprehensive dietary insights, enabling them to make more nuanced and tailored choices.

