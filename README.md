# Underwater-Plastic-Waste-Detection-With-YOLOv3-Algorithm
![Hasil testing sampah plastik di dalam air](https://github.com/pridanfad/Underwater-Plastic-Waste-Detection-With-YOLOv3-Algorithm/assets/102144951/17485e3c-e728-4e18-9039-4895c567bd54)

This repository contains the implementation of the YOLOv3 algorithm for Underwater Plastic Waste Detection. The steps involved in the process are outlined below:

## Steps
---
- **1. Compiling the dataset**
  - Image data in JPG format is collected using the web scraping technique using the Python programming language with the BeautifulSoup library.

- **2. Data Annotation**
  - The images is annotated with labelImg.py
  - The label only consist of 'plastic'
 
- **3. Training the YOLOv3 model**
  - The yolov3 model developed by Joseph Redmon https://github.com/AlexeyAB/darknet.git with the architecture shown below
    ![image](https://github.com/pridanfad/Underwater-Plastic-Waste-Detection-With-YOLOv3-Algorithm/assets/102144951/f36cde92-84f6-40e0-bf1d-9b5e9e68a87a)

- **4. Loss Function**
  - Provide details about the employed loss function used during the model training phase.
    ![256_Loss](https://github.com/pridanfad/Underwater-Plastic-Waste-Detection-With-YOLOv3-Algorithm/assets/102144951/b77b4e58-3377-45ce-a4f3-b391891dab17)

- **5. mAP**
  - Provide information about the mAP evaluation metric and its significance in assessing the model's accuracy.
    ![image](https://github.com/pridanfad/Underwater-Plastic-Waste-Detection-With-YOLOv3-Algorithm/assets/102144951/192bba8b-7088-4848-ae66-664994732d86)

- **6. Testing the YOLOv3 model in a controlled environment**
  - The trained model further tested in a controlled environment to evaluate the model's performance under varying water turbidity conditions.
  - ![Detection_Slightly Turbid Water_Red Plastic](https://github.com/pridanfad/Underwater-Plastic-Waste-Detection-With-YOLOv3-Algorithm/assets/102144951/1f569b04-26f5-4359-bd20-42df7c6804ba)
