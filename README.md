Laboratory Work 2-A Activity — Plant Species Image Classification Using Teachable Machine

Techable Machine Model: https://drive.google.com/drive/folders/1cGc_GKP0UrAEKyjXahZdafLjEaN25G2U?usp=sharing

A. Project Overview

Brief description of the project

-This project uses Teachable Machine to build an image classification model that can identify different types of flowers. The dataset consists of 20 flower classes, with 250 images per class, used to train the model to recognize visual patterns in flower images.

Purpose of the image classification model

-The purpose of the model is to automatically classify flower images into their correct categories, demonstrating how machine learning can be used for image recognition tasks.

B. Plant Species Section

<img width="279" height="618" alt="image" src="https://github.com/user-attachments/assets/aee37133-f10d-484f-bc95-2b07c357217f" />
<img width="261" height="619" alt="image" src="https://github.com/user-attachments/assets/1c10af80-330b-452d-b3e1-1744d28149bb" />
<img width="233" height="495" alt="image" src="https://github.com/user-attachments/assets/ba3bbb3b-de0e-4c5c-ad02-56d0639a08bf" />



Representative Image:

![images (5)](https://github.com/user-attachments/assets/c06391d9-ff93-4444-907d-42f5262017e5)

Common Name: Dahlia

Scientific Name: Dahlia spp.

Description of the Plant Species: Dahlia is a flowering plant known for its vibrant colors and layered petals. It comes in a wide variety of shapes and sizes and is commonly grown as an ornamental plant in gardens. Dahlias are valued for their beauty and are often used for decoration and floral arrangements.

C. Model Training Details

<img width="204" height="362" alt="image" src="https://github.com/user-attachments/assets/97b4f5b6-c675-42bd-b7c2-f6580acb43f5" />

Written explanation of why you chose those values
Answer: These values were chosen to keep the training stable, avoid overfitting, and achieve good accuracy for a multi-class image dataset.

D. Model Evaluation

<img width="260" height="560" alt="image" src="https://github.com/user-attachments/assets/a01f586a-6fe1-49d9-8dc1-853b5d4045c2" />

E. Model Testing

   <img width="154" height="557" alt="1" src="https://github.com/user-attachments/assets/3e40a143-c983-4dfe-b8cc-75e0c08ef91b" />

   <img width="154" height="557" alt="1" src="https://github.com/user-attachments/assets/49857e50-c0a4-4bc0-bc0e-f72cf77d05ad" />

   <img width="158" height="569" alt="3" src="https://github.com/user-attachments/assets/b3b4e1d9-67ba-4a20-a98a-d4514fab8a16" />

   <img width="195" height="567" alt="4" src="https://github.com/user-attachments/assets/dee7f847-2891-4fb5-b6f0-f6e01d4e9c80" />

   <img width="195" height="567" alt="4" src="https://github.com/user-attachments/assets/0a4a3b2b-ae99-4c19-94be-e5f7ab3c7a98" />

   <img width="153" height="552" alt="6" src="https://github.com/user-attachments/assets/1d78dbbb-4868-4b50-9f42-7ace06fad600" />

   <img width="187" height="563" alt="7" src="https://github.com/user-attachments/assets/505fb90d-fe00-4c6b-97dd-f3dcc17bfc71" />

   <img width="144" height="560" alt="8" src="https://github.com/user-attachments/assets/94680fd7-bc2e-47b2-9d32-91bcb172b669" />

   <img width="161" height="557" alt="9" src="https://github.com/user-attachments/assets/9c4f32e0-de8a-4237-99de-8b596f94a6ab" />

   <img width="165" height="561" alt="10" src="https://github.com/user-attachments/assets/b8b346b7-c244-42e7-a910-783a62cfbc59" />

   Reflection Questions:

Answer the following questions based on your experience:

1. How did the number of images per class affect your model’s accuracy?
   
   - The model was more accurate because there were 250 images per class, meaning that the model could learn more varieties of each flower, from different angles and under varying lighting conditions. Increasing the sample size also decreased bias and helped make the model predict consistently.
     
2. Which plant species were most commonly misclassified and why?
   
   -Some flower species with analogous colours, and petal shapes tended to be often mismatched. This occurs because some flowers have similar visual characteristics, in terms of petal composition and color patterns, so it becomes more difficult for the model to discriminate them.
   
3. How did changing the epochs, batch size, or learning rate affect the training results?
   
   -As the number of epochs was increased, accuracy increased until a certain point and tail went down given enough epoch. Modifying the batch size impacted training stability and speed, and reducing the learning rate led to smoother, more stable training with less accuracy zigzags.
   
4. What challenges did you encounter during dataset collection and labeling?
   
   -One of the major hurdles was that it was difficult to obtain uniform and high-quality images for each class. Correctly identifying samples and not duplicating or taking images which were too similar was also an issue, and even magnified with the use of augmented images.
   
5. If you were to improve your model, what specific changes would you make and why?

   -To improve the model, I would add more real and diverse images for each class instead of relying mostly on augmented images. I would also test different lighting conditions and backgrounds to help the model generalize better to real-world images.











   













