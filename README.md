# Plant-Disease-Monitoring-Expert-with-Supplements
This project aims to create an automated plant disease monitoring system powered by image recognition and machine learning. The system will analyze plant images captured through smartphones or dedicated cameras to detect visible symptoms of diseases. Upon identifying a disease, the system will recommend supplements, pesticides, or organic treatments to address the issue and improve the plant's health.

![Status](https://img.shields.io/badge/status-completed-brightgreen) 
![Version](https://img.shields.io/badge/version-1.0.0-blue) 
![License](https://img.shields.io/badge/license-MIT-green)
![Language](https://img.shields.io/badge/language-Python-orange) 
![Build](https://img.shields.io/badge/build-passing-brightgreen)

![Plant Image](https://cdn-images-1.medium.com/max/1200/1*FswlF4lZPQ4kT_gkybacZw.jpeg)

## Introduction

In recent times, environmental changes have adversely affected plants, resulting in decreased agricultural yields. Factors such as the overuse of fertilizers and pesticides contribute to this decline, ultimately impacting the economy reliant on agriculture. 

Implementing techniques for early disease detection can significantly assist farmers in efficiently cultivating crops both qualitatively and quantitatively. Thus, the ability to detect plant diseases plays a crucial role in modern agriculture.

By identifying crop diseases early, farmers can take preventive measures, ensuring better crop yields and sustainable farming practices.

## The PlantVillage Dataset

This project utilizes the publicly available and well-known PlantVillage Dataset, published by crowdAI during the [PlantVillage Disease Classification Challenge](https://www.crowdai.org/challenges/plantvillage-disease-classification-challenge).

The dataset comprises approximately **54,305 images** of plant leaves collected under controlled environmental conditions, spanning **14 different species**:

- **Apple**
- **Blueberry**
- **Cherry**
- **Corn**
- **Grape**
- **Orange**
- **Peach**
- **Bell Pepper**
- **Potato**
- **Raspberry**
- **Soybean**
- **Squash**
- **Strawberry**
- **Tomato**

It contains a total of **38 classes** of plant diseases and **1 class** of background images, including:

1. Apple Scab
2. Apple Black Rot
3. Apple Cedar Rust
4. Apple Healthy
5. Blueberry Healthy
6. Cherry Healthy
7. Cherry Powdery Mildew
8. Corn Gray Leaf Spot
9. Corn Common Rust
10. Corn Healthy
11. Corn Northern Leaf Blight
12. Grape Black Rot
13. Grape Black Measles
14. Grape Leaf Blight
15. Grape Healthy
16. Orange Huanglongbing
17. Peach Bacterial Spot
18. Peach Healthy
19. Bell Pepper Bacterial Spot
20. Bell Pepper Healthy
21. Potato Early Blight
22. Potato Healthy
23. Potato Late Blight
24. Raspberry Healthy
25. Soybean Healthy
26. Squash Powdery Mildew
27. Strawberry Healthy
28. Strawberry Leaf Scorch
29. Tomato Bacterial Spot
30. Tomato Early Blight
31. Tomato Late Blight
32. Tomato Leaf Mold
33. Tomato Septoria Leaf Spot
34. Tomato Two Spotted Spider Mite
35. Tomato Target Spot
36. Tomato Mosaic Virus
37. Tomato Yellow Leaf Curl Virus
38. Tomato Healthy

Due to limited computational power, training the classification model locally on standard machines can be challenging. To overcome this, we leverage the processing power of Google Colab, which provides easy access to a free TPU instance for efficient model training.


## Connect with Me

- [LinkedIn Profile](https://www.linkedin.com/in/aazam-shareef-234170171/)
- Email: aezamsos@gmail.com
- WhatsApp: +918328476955
