# Nvidia AI Specialist Certification

---


## **Title: Smarter Air Using YOLOv5 (AI for Better Living)**

---

## **OverView of the Project:**

- **Opening Background Information**:

 

Air purifiers are essential home appliances that improve indoor air quality in modern life, but it is often difficult for users to check the condition of the air purifier (such as whether it is operated or needs to be replaced with a filter).

Traditional air purifiers operate in a static rather than dynamic adaptation to changes in the external environment, and often require users to check their condition themselves.

To improve these limitations, we propose an air purifier condition monitoring system using AI.

- **General Description of the Current Project:**


This project aims to monitor the appearance and operation status of air purifiers in real time by using the YOLOv5 object detection model. It analyzes the performance and condition by detecting the LED indicators, placement status, and operation status of air purifiers, and provides useful information to users such as when to replace filters or deployment problems. Through this, we want to optimize the efficiency of air purifiers and improve the quality of life with AI-based smart air management solutions.

- **(Proposed Idea for Enhancements to the Project**


1. **Practical Application of AI Technology**: YOLOv5 can be used to detect the appearance and operational status of air purifiers in real time to overcome the limitations of existing air purifiers. This offers the potential for development as a smart management solution that goes beyond just air purification.
2. **Diverse scalability**: Although the current focus is on air purifiers, they are highly likely to expand into more complex indoor environmental management solutions in combination with human detection or air quality data.
3. **Improved user convenience:** Users can intuitively understand the condition of the air purifier (such as whether it is operating, filter replacement required, placement problems, etc.), reducing administrative hassle and helping to use it efficiently and sustainably.

- **Value and Significance of this Project:**


By using YOLOv5 to monitor the condition of the air purifier in real time, it enables easy management and efficient use for users. It automatically detects whether the air purifier is operated, placed, and needs to be maintained to improve the user experience and reduce energy consumption to support a sustainable environment. In addition, it presents the possibility of expanding into a smart home implementation and a future air management system through the convergence of AI and IoT technology, and contributes to the creation of a healthy indoor environment.

- **Current Limitations:**


In order to accurately detect the appearance and condition of air purifiers, we are facing limitations such as lack of data in various environments and securing the versatility of the model. In particular, we are concerned about the deterioration of detection performance in real user environments such as lighting conditions, angles, and backgrounds, and data augmentation and additional learning are needed to solve this problem. In addition, energy consumption and compatibility problems that occur in the process of real-time monitoring and smart home interworking require continuous improvement.

- **Literature Review:**

 
Air purifiers are essential products for improving indoor air quality, and existing studies mainly focused on air quality measurement using internal sensors or IoT-based control. On the other hand, YOLOv5 is being used as a technology to respond to environmental changes in various fields with its lightweight and real-time detection capabilities. This project focuses on overcoming the limitations of existing air purifiers and implementing smarter air management systems by applying these YOLOv5 technologies to monitor the appearance and condition of air purifiers.

## **Image Acquisition Method:**


1.The Air Purifier images were taken to test whether the YOLOv5 model can only accurately detect air purifiers in environments where air purifiers are present with other objects. They were used to verify the model's detection accuracy and to construct initial training data, including various lighting conditions, backgrounds, and surrounding objects.



2.The AirTest video was taken to verify that the air purifier can be accurately detected from various angles other than the front. The model is configured to recognize the appearance and analyze the condition from the side of the air purifier or an oblique angle. Through this, it was used to finally evaluate the detection range and real-time detection performance of YOLOv5 and to confirm the practicality of the model.

### **Air purifier and ambient object detection test**

1.https://drive.google.com/file/d/16tKD0hSN8TPibK38s08IRQDoooKwaBs9/view?usp=drive_link

### **Various angle detection verification of air purifiers**

2.https://drive.google.com/file/d/16ulDWSNdv-jO5Q2lN151Tz6g_dEld4vU/view?usp=drive_link

## **Learning Data Extraction and Learning Annotation**:


For learning with 640 resolution images on YOLOv5, images were made into 640 x 640 resolution images using Vllo.

### Video resolution adjustment

![image](https://github.com/user-attachments/assets/773d49d8-fe86-4f9c-9517-f70ab4e2dcd2)

link:[https://apps.apple.com/us/app/vllo-my-first-video-editor/id952050883](https://apps.apple.com/us/app/vllo-my-first-video-editor/id952050883)

![image](https://github.com/user-attachments/assets/c6c78457-53c4-4eec-a439-d4ca81b3ca15)

![image](https://github.com/user-attachments/assets/28f5bd22-1201-4db0-ae67-433db040abb1)


DarkLabel, also known as Video/Image Labeling and Annotation Tool, was used to image or annotate images made at 640 x 640 resolution in frame units.

### DarkLabel

[https://drive.google.com/drive/folders/1JurDKwZfmgUDdV_XLH7gVDldSI-KOUTC?usp=drive_link](https://drive.google.com/drive/folders/1JurDKwZfmgUDdV_XLH7gVDldSI-KOUTC?usp=drive_link)

![image](https://github.com/user-attachments/assets/a7a784a6-e36a-46de-9863-9c26e1cd2bd9)


First, select a 640 x 640 resolution image through Open Video. After that, labeled frames only activates the check mark.

![image](https://github.com/user-attachments/assets/aa9c5bdf-65d4-4255-b58a-4953556b86bf)


And you need to work through darklabel.yml before working on Annotation.

![image](https://github.com/user-attachments/assets/1b412efb-24a6-45db-bee1-eb81df853d09)


Create my_classes2 in the yaml file and add “Air purifier” for the class name.

![image (1)](https://github.com/user-attachments/assets/9f2c1abc-9095-4844-9f62-9fd8ab1689e5)


Now, when announcing, create a new format9 so that you can see the classes set in the DarkLabel GUI, and add a preset my_classes2 for classes_set, and set the name to be viewed in the GUI to Air purifier.

![image (1)](https://github.com/user-attachments/assets/d8f3d390-f91f-463e-bb80-cd1df7ba3642)


It can be seen that the 9th Air purifier was created in the DarkLabel program

![image (1)](https://github.com/user-attachments/assets/d87b8df8-a06b-4b6d-80e6-3cccfcab6957)


After selecting Box + Label as the one that had been imported from Dark Label through Open Video, the item that matched the class was notified as shown in the picture below. After the announcement was completed, a folder called labels was created through GT Save As, and then stored in that folder called images was created through as Images and stored in that folder.

![image (1)](https://github.com/user-attachments/assets/e0ed92c6-648f-4b66-bf4e-a0f16c7b01f0)


It can be seen that there are an annotated PNG file and txt file in the images folder and labels folder.

![image (1)](https://github.com/user-attachments/assets/11220a8a-9827-43bd-a6c0-7c09fd98641e)

![image (1)](https://github.com/user-attachments/assets/e723f872-0aaa-440a-8e74-5edbcbe3db1c)

### Air purifier images/labels:

https://drive.google.com/drive/folders/1XF6SLGeGCbdcRsFkMxD3uHgz5xgfw88j?usp=drive_link (i**mage folder)**

https://drive.google.com/drive/folders/1Ss5jZRuz2dOCYyDxQiiDTtJKWDen85GL?usp=drive_link (l**abel folder)**

## **Learning process with Google Colab**:


First, I connected the data to Google Drive using Colab provided by Google.

![image (1)](https://github.com/user-attachments/assets/9204345f-e361-4470-ad5c-6ea1c2773509)

![image (1)](https://github.com/user-attachments/assets/46b245e7-e351-49bc-9350-7ae621b8a468)

---

### **Install YOLOv5:**


After cloning YOLOv5 from GitHub to run the YOLOv5 model in a Google Colab environment, we installed the required package (requirements.txt). In addition, we set up a learning environment by installing an additional Pillow library (version 10.3) for image processing.

![image (1)](https://github.com/user-attachments/assets/cf0d913a-b3b8-42ac-aad1-c2a2e2e092f6)

### **Create Verification Data:**


In order to separate the training data from the verification data, 30% of the training data was separated into verification data using the create_validation_set function and stored in each images and labels directory. Data separation was performed randomly using the training_test_split function and the check_dataset function was used to verify that the data was properly separated by checking the number of image and label files of the training and Val data. This ensured the reliability of the training and verification datasets.

```python
##검증 데이터 만들기
import os
import shutil
from sklearn.model_selection import train_test_split

def create_validation_set(train_path, val_path, split_ratio=0.3):
    """
    Train 데이터의 일부를 Val로 이동
    """
    # 필요한 디렉토리 생성
    os.makedirs(os.path.join(val_path, 'images'), exist_ok=True)
    os.makedirs(os.path.join(val_path, 'labels'), exist_ok=True)

    # Train 이미지 리스트 가져오기
    train_images = os.listdir(os.path.join(train_path, 'images'))
    train_images = [f for f in train_images if f.endswith(('.jpg', '.jpeg', '.png'))]

    # Train/Val 분할
    _, val_images = train_test_split(train_images,
                                   test_size=split_ratio,
                                   random_state=42)

    # Val로 파일 복사
    for image_file in val_images:
        # 이미지 복사
        src_image = os.path.join(train_path, 'images', image_file)
        dst_image = os.path.join(val_path, 'images', image_file)
        shutil.copy2(src_image, dst_image)

        # 라벨 파일 복사
        label_file = os.path.splitext(image_file)[0] + '.txt'
        src_label = os.path.join(train_path, 'labels', label_file)
        dst_label = os.path.join(val_path, 'labels', label_file)
        if os.path.exists(src_label):
            shutil.copy2(src_label, dst_label)

    print(f"Created validation set with {len(val_images)} images")

# 실행
train_path = '/content/drive/MyDrive/yolov5/Train'
val_path = '/content/drive/MyDrive/yolov5/Val'

create_validation_set(train_path, val_path)
```

```python
def check_dataset():
    train_path = '/content/drive/MyDrive/yolov5/Train'
    val_path = '/content/drive/MyDrive/yolov5/Val'

    # Train 데이터 확인
    train_images = len(os.listdir(os.path.join(train_path, 'images')))
    train_labels = len(os.listdir(os.path.join(train_path, 'labels')))

    # Val 데이터 확인
    val_images = len(os.listdir(os.path.join(val_path, 'images')))
    val_labels = len(os.listdir(os.path.join(val_path, 'labels')))

    print("Dataset status:")
    print(f"Train - Images: {train_images}, Labels: {train_labels}")
    print(f"Val - Images: {val_images}, Labels: {val_labels}")

# 데이터셋 상태 확인
check_dataset()
```

### **Getting Started with Learning:**

```python
!python /content/drive/MyDrive/yolov5/train.py  --img 640 --batch 16 --epochs 300 --data /content/drive/MyDrive/yolov5/data.yaml --weights yolov5n.pt --cache
```


1.**Run the train.py script**

Model training was performed using YOLOv5's formal learning script ([train.py](http://train.py/) ).

2.**Setting Learning Parameters**

`--img 640`: I set the size of the input image to 640x640 pixels, allowing the model to learn high-resolution information.

`--batch 16`:The batch size was set to 16 to balance the learning speed and memory usage.

`--epochs 300`:The training was performed for 300 epochs to allow the model to learn enough data.

`--data /content/drive/MyDrive/yolov5/data.yaml`:You specified the dataset configuration file data.yaml to provide training/validation data paths and class information for learning.

`--weights yolov5n.pt`:Utilizing YOLOv5n(nano) pre-learning weights, we have improved the learning initial performance and accelerated the learning speed.

`--cache`:By caching datasets into memory, we speed up learning and reduce I/O bottlenecks.

### **Verifying Learning:**

The code was executed to evaluate the detection performance of the trained YOLOv5 model and to verify that it accurately detects objects related to air purifiers, as a result.

```python
!python /content/drive/MyDrive/yolov5/detect.py --weights /content/drive/MyDrive/yolov5/runs/train/exp/weights/best.pt --img 640 --conf 0.1 --source /content/drive/MyDrive/yolov5/Train/images
```

![image (1)](https://github.com/user-attachments/assets/57a098a2-c24c-489f-a4c2-2f158cfaa7bd)

![image (1)](https://github.com/user-attachments/assets/775f139d-ed73-44dd-8040-b8aa731c9e6d)

![image (1)](https://github.com/user-attachments/assets/1cd86799-f86e-4150-92b2-5786980d3ae9)

![image (1)](https://github.com/user-attachments/assets/a521a83c-e91a-43d6-914c-07e2658a708c)

![image (1)](https://github.com/user-attachments/assets/f6cd1895-f89e-43d8-924d-f6dc080d36c8)

![image (1)](https://github.com/user-attachments/assets/19b9e096-358f-4a4b-8df7-5a2b78eef9d0)

![image (1)](https://github.com/user-attachments/assets/ea17a329-9cd2-4144-bfb0-f06b11e8e924)

![image (1)](https://github.com/user-attachments/assets/98b5f0e1-e3be-4452-abfa-bcac953271b7)

![train_batch0](https://github.com/user-attachments/assets/8dab3d7f-b07d-416b-9f26-8321c28d4ceb)

![train_batch1](https://github.com/user-attachments/assets/5478ada4-dc44-45cf-a935-9eda3ad27e51)

![train_batch2](https://github.com/user-attachments/assets/5783e7f3-cc6e-427f-a0fc-7b055f8af8bb)

![image (1)](https://github.com/user-attachments/assets/638d9dd6-4359-4cac-8a64-4aa7a58c8e7c)

![image (1)](https://github.com/user-attachments/assets/71261e45-7fba-48a3-a08d-aa998ccced87)

![labels](https://github.com/user-attachments/assets/78cf01b1-0138-4196-a375-40a1edc2c7ef)

![e739a2f7-d09c-46a6-9970-5135aa2cc4e5](https://github.com/user-attachments/assets/02e5eacd-2e5d-497f-a9bb-8c99952c9bea)

![3c9a40f3-c91b-40d5-a566-5d4b282a19a6](https://github.com/user-attachments/assets/d48052a3-3a1c-4622-b2aa-90e780d0a226)

![c9063196-8734-4dea-81b8-234716509002](https://github.com/user-attachments/assets/d72143a4-38c2-4ea6-b0ac-af0e3d37df6a)


This is the code that uses Airpurifier,AirTest images as inputs to evaluate the detection performance of the learned YOLOv5 model and verify that objects related to air purifiers can be detected from various angles.

```python
!python /content/drive/MyDrive/yolov5/detect.py --weights /content/drive/MyDrive/yolov5/runs/train/exp/weights/best.pt --img 640 --conf 0.1 --source /content/drive/MyDrive/AirTest.mp4
```

```python
!python /content/drive/MyDrive/yolov5/detect.py --weights /content/drive/MyDrive/yolov5/runs/train/exp/weights/best.pt --img 640 --conf 0.1 --source /content/drive/MyDrive/ Airpurifier.mp4
```

the original video

https://drive.google.com/file/d/1UtXmw4cmVDTk-WL-W6pmOjwJN573Qr9V/view?usp=drive_link

Verification video

https://drive.google.com/file/d/16u3VbUpRtT3ot1iuFiJN0sTpviL35BrH/view?usp=drive_link

the original video

https://drive.google.com/file/d/16ulDWSNdv-jO5Q2lN151Tz6g_dEld4vU/view?usp=drive_link

Verification video

https://drive.google.com/file/d/16wzFIfMkHmueKMGWgoSHxeP_tK3fqb51/view?usp=drive_link


Final Google Drive YOLOv5 file.

https://drive.google.com/drive/folders/1XogKFfQdIBZR6uKEqSeX-gfkOMJZK71R?usp=drive_link

### **Finish:**


Through this project, we were able to implement an air purifier detection and condition monitoring system using YOLOv5 and explore the practical application potential of AI technology in depth. It was a very meaningful time to expand technical understanding and present new possibilities for incorporating AI into air purifiers while directly carrying out the process from data preprocessing to learning and verification.

Finally, thank you for reviewing this report.😊
