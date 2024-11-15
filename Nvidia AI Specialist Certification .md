# Nvidia AI Specialist Certification

---

## **주제: YOLOv5를 이용한 Smarter Air (AI for Better Living)**

## **Title: Smarter Air Using YOLOv5 (AI for Better Living)**

---

## **프로젝트 개요 (OverView of the Project):**

- **배경 정보 소개(Opening Background Information)**:

 

공기청정기는 현대 생활에서 실내 공기질을 개선하는 필수 가전제품이지만, 사용자는 종종 공기청정기의 상태(작동 여부, 필터 교체 필요 여부 등)를 확인하기 어렵습니다.
기존의 공기청정기는 외부 환경 변화에 대한 동적 적응보다는 정적인 방식으로 작동하며, 사용자가 직접 상태를 점검해야 할 때가 많습니다.
이러한 한계를 개선하기 위해 AI를 활용한 공기청정기 상태 모니터링 시스템을 제안합니다.

Air purifiers are essential home appliances that improve indoor air quality in modern life, but it is often difficult for users to check the condition of the air purifier (such as whether it is operated or needs to be replaced with a filter).

Traditional air purifiers operate in a static rather than dynamic adaptation to changes in the external environment, and often require users to check their condition themselves.

To improve these limitations, we propose an air purifier condition monitoring system using AI.

- **프로젝트의 전반적인 설명 (General Description of the Current Project):**

이 프로젝트는 YOLOv5 객체 탐지 모델을 활용해 공기청정기의 외관과 작동 상태를 실시간으로 모니터링하는 것을 목표로 합니다. 공기청정기의 LED 표시등, 배치 상태, 작동 여부 등을 감지하여 성능과 상태를 분석하고, 사용자에게 필터 교체 시기나 배치 문제 등 유용한 정보를 제공합니다. 이를 통해 공기청정기의 효율성을 최적화하고, AI 기반의 스마트 공기 관리 솔루션으로 삶의 질을 향상시키고자 합니다.

This project aims to monitor the appearance and operation status of air purifiers in real time by using the YOLOv5 object detection model. It analyzes the performance and condition by detecting the LED indicators, placement status, and operation status of air purifiers, and provides useful information to users such as when to replace filters or deployment problems. Through this, we want to optimize the efficiency of air purifiers and improve the quality of life with AI-based smart air management solutions.

- **제안하고 싶은 프로젝트의 강점 (Proposed Idea for Enhancements to the Project):**
1. **AI 기술의 실용적 적용**: YOLOv5를 활용해 공기청정기의 외관 및 작동 상태를 실시간으로 감지하여 기존 공기청정기의 한계를 극복할 수 있습니다. 이는 단순히 공기 정화 기능을 넘어선 스마트 관리 솔루션으로 발전 가능성을 제공합니다.

2. **다양한 확장성**: 현재는 공기청정기에 초점을 맞추고 있지만, 사람 탐지나 공기질 데이터와 결합하여 더 복합적인 실내 환경 관리 솔루션으로 확장 가능성이 큽니다.

 3. **사용자 편의성 향상:**사용자는 공기청정기의 상태(작동 여부, 필터 교체 필요, 배치 문제 등)를 직관적으로 파악할 수 있어 관리의 번거로움을 줄이고, 효율적이고 지속 가능한 사용을 돕습니다.

1. **Practical Application of AI Technology**: YOLOv5 can be used to detect the appearance and operational status of air purifiers in real time to overcome the limitations of existing air purifiers. This offers the potential for development as a smart management solution that goes beyond just air purification.
2. **Diverse scalability**: Although the current focus is on air purifiers, they are highly likely to expand into more complex indoor environmental management solutions in combination with human detection or air quality data.
3. **Improved user convenience:** Users can intuitively understand the condition of the air purifier (such as whether it is operating, filter replacement required, placement problems, etc.), reducing administrative hassle and helping to use it efficiently and sustainably.

- **프로젝트의 가치와 중요성 ( Value and Significance of this Project):**

YOLOv5를 활용해 공기청정기의 상태를 실시간으로 모니터링함으로써, 사용자에게 간편한 관리와 효율적인 사용을 가능하게 합니다. 공기청정기의 작동 여부, 배치 상태, 유지 필요성을 자동으로 감지하여 사용자 경험을 향상시키고, 에너지 소비를 줄여 지속 가능한 환경을 지원합니다. 또한, AI와 IoT 기술의 융합을 통해 스마트홈 구현과 미래형 공기 관리 시스템으로 확장 가능성을 제시하며, 건강한 실내 환경 조성에 기여합니다.

By using YOLOv5 to monitor the condition of the air purifier in real time, it enables easy management and efficient use for users. It automatically detects whether the air purifier is operated, placed, and needs to be maintained to improve the user experience and reduce energy consumption to support a sustainable environment. In addition, it presents the possibility of expanding into a smart home implementation and a future air management system through the convergence of AI and IoT technology, and contributes to the creation of a healthy indoor environment.

- **직면하고 있는 한계 (Current Limitations):**

공기청정기의 외관과 상태를 정확히 탐지하기 위해 다양한 환경에서의 데이터 부족과 모델의 범용성 확보라는 한계를 직면하고 있습니다. 특히 조명 조건, 각도, 배경 등 실제 사용자 환경에서의 탐지 성능 저하가 우려되며, 이를 해결하기 위해 데이터 증강과 추가적인 학습이 필요합니다. 또한, 실시간 모니터링과 스마트홈 연동 구현 과정에서 발생하는 에너지 소비와 호환성 문제도 지속적인 개선이 요구됩니다.

In order to accurately detect the appearance and condition of air purifiers, we are facing limitations such as lack of data in various environments and securing the versatility of the model. In particular, we are concerned about the deterioration of detection performance in real user environments such as lighting conditions, angles, and backgrounds, and data augmentation and additional learning are needed to solve this problem. In addition, energy consumption and compatibility problems that occur in the process of real-time monitoring and smart home interworking require continuous improvement.

- **문헌 고찰 (Literature Review):**

공기청정기는 실내 공기질 개선을 위한 필수 제품으로, 기존 연구는 주로 내부 센서를 활용한 공기질 측정이나 IoT 기반 제어에 초점을 맞췄습니다. 반면, YOLOv5는 경량성과 실시간 탐지 능력으로 다양한 분야에서 환경 변화에 대응하는 기술로 활용되고 있습니다. 본 프로젝트는 이러한 YOLOv5 기술을 공기청정기의 외관 및 상태 모니터링에 적용해 기존 공기청정기의 한계를 극복하고, 더 스마트한 공기 관리 시스템을 구현하는 데 초점을 맞춥니다.

Air purifiers are essential products for improving indoor air quality, and existing studies mainly focused on air quality measurement using internal sensors or IoT-based control. On the other hand, YOLOv5 is being used as a technology to respond to environmental changes in various fields with its lightweight and real-time detection capabilities. This project focuses on overcoming the limitations of existing air purifiers and implementing smarter air management systems by applying these YOLOv5 technologies to monitor the appearance and condition of air purifiers.

## **영상 취득 방법 (Image Acquisition Method):**

1. Air Purifier 영상은 공기청정기가 다른 물체와 함께 있는 환경에서 YOLOv5 모델이 공기청정기만 정확히 탐지할 수 있는지 테스트하기 위해 촬영되었습니다. 다양한 조명 조건과 배경, 주변 물체를 포함해 모델의 탐지 정확도를 검증하고 초기 학습 데이터를 구성하는 데 사용되었습니다.

The Air Purifier images were taken to test whether the YOLOv5 model can only accurately detect air purifiers in environments where air purifiers are present with other objects. They were used to verify the model's detection accuracy and to construct initial training data, including various lighting conditions, backgrounds, and surrounding objects.

1. AirTest 영상은 공기청정기가 정면 외의 다양한 각도에서도 정확히 탐지될 수 있는지를 검증하기 위해 촬영되었습니다. 모델이 공기청정기의 옆면이나 비스듬한 각도에서도 외관을 인식하고 상태를 분석할 수 있도록 구성되었습니다. 이를 통해 YOLOv5의 탐지 범위와 실시간 탐지 성능을 최종적으로 평가하고, 모델의 실용성을 확인하는 데 활용되었습니다.

The AirTest video was taken to verify that the air purifier can be accurately detected from various angles other than the front. The model is configured to recognize the appearance and analyze the condition from the side of the air purifier or an oblique angle. Through this, it was used to finally evaluate the detection range and real-time detection performance of YOLOv5 and to confirm the practicality of the model.

### 1.공기청정기와 주변 물체 탐지 테스트(**Air purifier and ambient object detection test)**

1.https://drive.google.com/file/d/16tKD0hSN8TPibK38s08IRQDoooKwaBs9/view?usp=drive_link

### 2.공기청정기 다양한 각도 탐지 검증(**Various angle detection verification of air purifiers)**

2.https://drive.google.com/file/d/16ulDWSNdv-jO5Q2lN151Tz6g_dEld4vU/view?usp=drive_link

## 학습 데이터 추출과 학습 어노테이션 (**Learning Data Extraction and Learning Annotation)**:

YOLOv5에서 640 해상도 이미지로 학습하기 위해서 Vllo를 사용하여 영상을 640 x 640 해상도 영상으로 만들었다. 

For learning with 640 resolution images on YOLOv5, images were made into 640 x 640 resolution images using Vllo.

### 비디오 해상 조정 (Video resolution adjustment)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image.png)

link:[https://apps.apple.com/us/app/vllo-my-first-video-editor/id952050883](https://apps.apple.com/us/app/vllo-my-first-video-editor/id952050883)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%201.png)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%202.png)

640 x 640 해상도로 만들어진 영상을 프레임 단위로 이미지로 만들거나 어노테이션을 하기 위해서 Video/Image Labeling and Annotation Tool로 잘 알려진 DarkLabel을 사용했다.

DarkLabel, also known as Video/Image Labeling and Annotation Tool, was used to image or annotate images made at 640 x 640 resolution in frame units.

### DarkLabel

[https://drive.google.com/drive/folders/1JurDKwZfmgUDdV_XLH7gVDldSI-KOUTC?usp=drive_link](https://drive.google.com/drive/folders/1JurDKwZfmgUDdV_XLH7gVDldSI-KOUTC?usp=drive_link)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%203.png)

먼저 Open Video를 통해 640 x 640 해상도 영상을 선택한다. 이후 labeled frames only가 체크 표시를 활성화 한다. 

First, select a 640 x 640 resolution image through Open Video. After that, labeled frames only activates the check mark.

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%204.png)

먼저 Annotation작업을 하기전에 darklabel.yml을 통해 작업을해야한다.

First, you need to work through darklabel.yml before you can work on Annotation.

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%205.png)

yaml 파일 안에 my_classes2 를 만들고 class명은 “Air purifier”을 추가한다.

Create my_classes2 in the yaml file and add “Air purifier” for the class name.

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%206.png)

이제 Annotation할 때 DarkLabel GUI에서 설정한 classes를 볼 수 있게 format9를 새로 생성하고 classes_set은 미리 설정해 놓은 my_classes2를 넣고 GUI에서 볼 name을 Air purifier으로 설정한다.

Now, when announcing, create a new format9 so that you can see the classes set in the DarkLabel GUI, and add a preset my_classes2 for classes_set, and set the name to be viewed in the GUI to Air purifier.

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%207.png)

DarkLabel 프로그램에 9번째인 Air purifier가 생성이 된 것을 확인할 수 있다

It can be seen that the 9th Air purifier was created in the DarkLabel program

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%208.png)

DarkLabel에서 Open Video를 통해 영상을 불러왔던것을 Box + Label로 선택 후 아래 사진과 같이 해당 class에 부합하는 물건에 Annotation을 했다. Annotation이 끝난 후 GT Save As를 통해 labels라는 폴더를 만들고 해당 폴더 안에 저장하고 as Images를 통해 images라는 폴더를 만들고 해당 폴더안에 저장했다.

After selecting Box + Label as the one that had been imported from Dark Label through Open Video, the item that matched the class was notified as shown in the picture below. After the announcement was completed, a folder called labels was created through GT Save As, and then stored in that folder called images was created through as Images and stored in that folder.

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%209.png)

images폴더와 labels폴더 안에 Annotation한 PNG파일과 txt파일이 있음을 확인할 수 있다.

It can be seen that there are an annotated PNG file and txt file in the images folder and labels folder.

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2010.png)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2011.png)

### Air purifier images/labels:

https://drive.google.com/drive/folders/1XF6SLGeGCbdcRsFkMxD3uHgz5xgfw88j?usp=drive_link (i**mage folder)**

https://drive.google.com/drive/folders/1Ss5jZRuz2dOCYyDxQiiDTtJKWDen85GL?usp=drive_link (l**abel folder)**

## Gogle Colab을 통한 학습 과정(**Learning process with Google Colab)**:

먼저 Google에서 제공하는 Colab을 이용하여 구글 드라이브에 데이터를 연결 하였습니다.

First, I connected the data to Google Drive using Colab provided by Google.

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2012.png)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2013.png)

---

### **YOLOv5 설치(Install YOLOv5):**

Google Colab 환경에서 YOLOv5 모델을 실행하기 위해 GitHub에서 YOLOv5를 클론한 후, 필수 패키지(requirements.txt)를 설치했습니다. 또한, 이미지 처리를 위해 `Pillow` 라이브러리(버전 10.3)를 추가적으로 설치하여 학습 환경을 설정했습니다.

After cloning YOLOv5 from GitHub to run the YOLOv5 model in a Google Colab environment, we installed the required package (requirements.txt). In addition, we set up a learning environment by installing an additional Pillow library (version 10.3) for image processing.

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2014.png)

### **검증 데이터 만들기(Create Verification Data):**

학습 데이터와 검증 데이터를 분리하기 위해 `create_validation_set` 함수를 사용하여 학습 데이터의 30%를 검증 데이터로 분리하고, 각각의 `images`와 `labels` 디렉토리에 저장하였습니다. 데이터 분리는 `train_test_split` 함수를 활용해 랜덤하게 수행되었으며, `check_dataset` 함수를 통해 Train과 Val 데이터의 이미지 및 라벨 파일 개수를 확인하여 데이터가 올바르게 분리되었음을 검증했습니다. 이를 통해 학습과 검증 데이터셋의 신뢰성을 확보하였습니다.

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

### **학습 시작하기(Getting Started with Learning):**

```python
#모델 학습하기
!python /content/drive/MyDrive/yolov5/train.py  --img 640 --batch 16 --epochs 300 --data /content/drive/MyDrive/yolov5/data.yaml --weights yolov5n.pt --cache
```

1.**`train.py` 스크립트 실행**
YOLOv5의 공식 학습 스크립트(`train.py`)를 사용하여 모델 학습을 수행했습니다.

2.**학습 파라미터 설정**

`--img 640`: 입력 이미지의 크기를 640x640 픽셀로 설정하여 모델이 고해상도의 정보를 학습할 수 있도록 했습니다.
`--batch 16`: 배치 크기를 16으로 설정하여 학습 속도와 메모리 사용량의 균형을 맞췄습니다.
`--epochs 300`: 학습을 300 에폭 동안 수행하여 모델이 충분히 데이터를 학습할 수 있도록 했습니다.
`--data /content/drive/MyDrive/yolov5/data.yaml`: 데이터셋 구성 파일 `data.yaml`을 지정하여 학습에 사용할 Train/Validation 데이터 경로와 클래스 정보를 제공했습니다.
`--weights yolov5n.pt`: YOLOv5n(nano) 사전 학습 가중치를 활용하여 학습 초기 성능을 향상시키고 학습 속도를 높였습니다.
`--cache`: 데이터셋을 메모리에 캐싱하여 학습 속도를 높이고 I/O 병목 현상을 줄였습니다.

1.**Run the train.py script**

Model training was performed using YOLOv5's formal learning script ([train.py](http://train.py/) ).

2.**Setting Learning Parameters**

`--img 640`: I set the size of the input image to 640x640 pixels, allowing the model to learn high-resolution information.

`--batch 16`:The batch size was set to 16 to balance the learning speed and memory usage.

`--epochs 300`:The training was performed for 300 epochs to allow the model to learn enough data.

`--data /content/drive/MyDrive/yolov5/data.yaml`:You specified the dataset configuration file data.yaml to provide training/validation data paths and class information for learning.

`--weights yolov5n.pt`:Utilizing YOLOv5n(nano) pre-learning weights, we have improved the learning initial performance and accelerated the learning speed.

`--cache`:By caching datasets into memory, we speed up learning and reduce I/O bottlenecks.

### **학습 검증하기(Verifying Learning):**

 학습된 YOLOv5 모델의 탐지 성능을 평가하고 공기청정기와 관련된 객체를 정확히 탐지하는지 검증하기 위해 실행한 코드이며, 그 결과입니다.

The code was executed to evaluate the detection performance of the trained YOLOv5 model and to verify that it accurately detects objects related to air purifiers, as a result.

```python
!python /content/drive/MyDrive/yolov5/detect.py --weights /content/drive/MyDrive/yolov5/runs/train/exp/weights/best.pt --img 640 --conf 0.1 --source /content/drive/MyDrive/yolov5/Train/images
```

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2015.png)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2016.png)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2017.png)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2018.png)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2019.png)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2020.png)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2021.png)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2022.png)

![train_batch0.jpg](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/train_batch0.jpg)

![train_batch1.jpg](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/train_batch1.jpg)

![train_batch2.jpg](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/train_batch2.jpg)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2023.png)

![image.png](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/image%2024.png)

![labels.jpg](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/labels.jpg)

![e739a2f7-d09c-46a6-9970-5135aa2cc4e5.jpg](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/e739a2f7-d09c-46a6-9970-5135aa2cc4e5.jpg)

![3c9a40f3-c91b-40d5-a566-5d4b282a19a6.jpg](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/3c9a40f3-c91b-40d5-a566-5d4b282a19a6.jpg)

![c9063196-8734-4dea-81b8-234716509002.jpg](Nvidia%20AI%20Specialist%20Certification%2013fabca9fc008098a99eef6b91440d0b/c9063196-8734-4dea-81b8-234716509002.jpg)

학습된 YOLOv5 모델의 탐지 성능을 평가하고, 공기청정기와 관련된 객체를 다양한 각도에서 탐지할 수 있는지 검증하기 위해 Airpurifier,AirTest영상을 입력으로 사용한 코드이며, 그 결과입니다.

This is the code that uses Airpurifier,AirTest images as inputs to evaluate the detection performance of the learned YOLOv5 model and verify that objects related to air purifiers can be detected from various angles.

```python
!python /content/drive/MyDrive/yolov5/detect.py --weights /content/drive/MyDrive/yolov5/runs/train/exp/weights/best.pt --img 640 --conf 0.1 --source /content/drive/MyDrive/AirTest.mp4
```

```python
!python /content/drive/MyDrive/yolov5/detect.py --weights /content/drive/MyDrive/yolov5/runs/train/exp/weights/best.pt --img 640 --conf 0.1 --source /content/drive/MyDrive/ Airpurifier.mp4
```

원본 영상(the original video)

https://drive.google.com/file/d/1UtXmw4cmVDTk-WL-W6pmOjwJN573Qr9V/view?usp=drive_link

검증 영상(Verification video)

https://drive.google.com/file/d/16u3VbUpRtT3ot1iuFiJN0sTpviL35BrH/view?usp=drive_link

원본 영상(the original video)

https://drive.google.com/file/d/16ulDWSNdv-jO5Q2lN151Tz6g_dEld4vU/view?usp=drive_link

검증 영상(Verification video)

https://drive.google.com/file/d/16wzFIfMkHmueKMGWgoSHxeP_tK3fqb51/view?usp=drive_link

최종 구글 드라이브 YOLOv5 파일입니다.

Final Google Drive YOLOv5 file.

https://drive.google.com/drive/folders/1XogKFfQdIBZR6uKEqSeX-gfkOMJZK71R?usp=drive_link

### **마무리(Finish):**

이번 프로젝트를 통해 YOLOv5를 활용하여 공기청정기 탐지와 상태 모니터링 시스템을 구현하며, AI 기술의 실질적인 응용 가능성을 깊이 탐구할 수 있었습니다. 데이터 전처리부터 학습과 검증까지의 과정을 직접 수행하면서 기술적 이해를 넓히고, 공기청정기에 AI를 접목하는 새로운 가능성을 제시할 수 있어 매우 뜻깊은 시간이었습니다.

마지막으로, 이 보고서를 검토해주셔서 감사합니다. 😊

Through this project, we were able to implement an air purifier detection and condition monitoring system using YOLOv5 and explore the practical application potential of AI technology in depth. It was a very meaningful time to expand technical understanding and present new possibilities for incorporating AI into air purifiers while directly carrying out the process from data preprocessing to learning and verification.

Finally, thank you for reviewing this report.😊


---
layout: post
title: "Notion으로 글 작성하고 Github io로 글 옮기기"
subtitle: "[Tips]"
date: 2020-03-02 17:00
background: 
tag: [Tips, Github io, Notion]
---
