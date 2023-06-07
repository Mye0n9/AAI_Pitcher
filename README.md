# AAI_Pitcher

Project Object: This project aims to classify baseball pitcher's wrist, elbow, and shoulder by utilizing CNN (Convolutional Neural Network). We hope to develop this project by applying it to object detection models, such as R-CNN, Fast-RCNN, Faster-RCNN, Yolo.

Dataset: https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=488
Dataset with only pitchers: 
- Image: https://drive.google.com/drive/folders/1ykBMAZSSr6haiWzCGgCzNHcN33JotP_P?usp=drive_link
- Label: https://drive.google.com/drive/folders/1yecH1esS9TAiyCVlojk_O55aJlNbrcdD?usp=drive_link

Data Preprocessing: We've changed the image data into numpy array and resized it by dividing it into 255. Then, cropped it by using label data and saved the numpy vals into pkl file
- Preprocessed: https://drive.google.com/drive/folders/1dKuSN0ke1oKVCUdPxrgOLqz4NH7fdubc?usp=drive_link

CNN Model: 3 layered with input of (1, 32, 32, 3) numpy array.

![다운로드](https://github.com/Mye0n9/AAI_Pitcher/assets/113423383/129b097d-2969-48cb-be84-1305ad7ba705)
