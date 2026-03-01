# Vehicle Detection and Counting System

A real-time deep learning–based vehicle detection and counting system built using modern object detection algorithms. The system detects and counts vehicles in video streams using **YOLOv8n**, providing fast and accurate performance suitable for intelligent transportation and smart city applications.


## 🚗 Project Overview

This project applies state-of-the-art deep learning techniques to detect and count:

* Cars
* Buses
* Trucks

The system processes video frames in real time and uses a **line-crossing technique** to count vehicles as they pass a predefined virtual line.

Tracking is handled through lightweight NumPy-based logic, ensuring efficient performance without heavy external tracking frameworks.


## 🎯 Why This Work Is Important

Vehicle detection and counting systems are widely used in:

* Intelligent Transportation Systems (ITS)
* Smart city traffic monitoring
* Road congestion analysis
* Highway safety management
* Automated toll collection systems
* Urban planning and infrastructure research

Deep learning–based approaches such as YOLO provide:

* Higher detection accuracy
* Better robustness in complex environments
* Real-time performance
* Strong generalization capability

Compared to classical computer vision methods, modern deep learning models significantly improve detection reliability under varying lighting, weather, and traffic conditions.


## 🔬 Future Research Possibilities

This project provides a strong foundation for advanced research in AI-driven transportation systems.

### 1️⃣ Real-Time Traffic Analytics

* Multi-lane vehicle tracking
* Speed estimation
* Density-based congestion prediction
* Real-time optimization using TensorRT, ONNX, or model quantization


### 2️⃣ Advanced Deep Learning Models

* Transformer-based object detectors (e.g., DETR family)
* Lightweight edge models for embedded deployment
* Multi-object tracking (MOT) integration
* Multi-class detection and behavioral classification


### 3️⃣ Traffic Behavior Understanding

* Illegal lane-changing detection
* Red-light violation detection
* Accident risk prediction using trajectory analysis
* Temporal deep learning models (LSTM, TCN) for behavior classification


### 4️⃣ High-Level Transportation Research

* Statistical traffic flow modeling
* Automated urban planning analysis
* GIS data integration
* Predictive traffic demand modeling


### 5️⃣ Smart-City & IoT Integration

* Cloud-based monitoring dashboards
* Distributed multi-camera systems
* Low-power embedded deployments
* Intelligent traffic control integration


## 🌍 Real-World Applications

This type of system is commonly used in:

* Highway monitoring systems
* Smart city surveillance networks
* Urban traffic control centers
* Toll booth automation
* Intelligent parking systems
* Public transportation scheduling systems

These technologies are widely adopted by transportation authorities, road-safety agencies, and smart-city solution providers worldwide.


# 🧠 Installation & Setup

## Step 1

Download or clone the source code and open the project folder in PyCharm (or your preferred IDE).

---

## Step 2

Open the terminal and install the required dependencies:

```bash
pip install absl-py attrs backcall cachetools certifi charset-normalizer click cmake colorama cvzone cycler cython decorator filterpy flatbuffers fonttools future geographiclib geopy google-auth google-auth-oauthlib greenlet grpcio idna imageio importlib-metadata ipython iso8601 itsdangerous jedi joblib kivy kivy-deps.angle kivy-deps.glew kivy-deps.sdl2 kiwisolver markdown markupsafe matplotlib matplotlib-inline mouseinfo network numpy oauthlib opencv-python packaging pandas parso phonenumbers pickleshare pillow prompt-toolkit protobuf psutil pyasn1 pyasn1-modules pyaudio pyautogui pycocotools-windows pygetwindow pygments pymsgbox pyparsing pyperclip pypiwin32 pyrect pyscreeze pyserial python-dateutil pytweening pytz pywavelets pywin32 pyyaml pyzbar requests requests-oauthlib rsa scikit-image scikit-learn scipy seaborn sentry-sdk serial six sklearn tensorboard tensorboard-data-server tensorboard-plugin-wit thop threadpoolctl tifffile torch torchvision tqdm traitlets typing_extensions ultralytics urllib3 vidstream wcwidth werkzeug zipp
```

Wait until all packages are installed successfully.


## Step 3

Run the main Python file:

```bash
python main.py
```

The system will start detecting and counting vehicles in real time.


## 📊 Output

The system generates:

* Real-time annotated video output
* Vehicle count display
* Line-crossing detection visualization
* Saved processed results (if enabled)

<img width="1365" height="725" alt="Screenshot_1" src="https://github.com/user-attachments/assets/f5788d09-22b4-4408-ae0c-aec3f5c7e692" />
<img width="1365" height="729" alt="Screenshot_2" src="https://github.com/user-attachments/assets/19edb57f-76b1-4457-98db-f22583d5dfea" />
<img width="1358" height="725" alt="Screenshot_3" src="https://github.com/user-attachments/assets/8e3833bd-22f5-486a-b648-898421d78271" />
<img width="1365" height="727" alt="Screenshot_4" src="https://github.com/user-attachments/assets/d229d4b2-8698-4bee-b067-2ebc1d1fd92b" />



## 📄 License

This project is developed for academic, research, and educational purposes.
You are free to use, modify, and extend it for further research and development.





**Vehicle Detection and Counting Using (Deep learning NumPy YOLOv8)**

This project applies modern deep-learning–based object detection to identify and count vehicles in video streams. YOLOv8 provides fast and accurate detection of cars, buses, and trucks, while tracking is handled through lightweight NumPy-based operations. The system works frame-by-frame in real time and generates vehicle counts using a line-crossing technique.

**Why This Work Is Important**

Vehicle detection and counting are widely used in

      Intelligent transportation systems

      Smart city traffic monitoring

      Road congestion analysis

      Highway safety management

      Automated toll systems

      Urban planning and infrastructure research

Deep-learning-based methods like YOLO are commonly used in these fields because they provide higher accuracy and better robustness than classical computer-vision techniques.


**Future Research Possibilities**

This project can grow into several strong research directions:

**1. Real-Time Traffic Analytics**

      Multi-lane vehicle tracking

      Speed estimation

      Density-based congestion prediction

      Real-time performance optimization (TensorRT, ONNX, quantization)

**2. Advanced Deep Learning Models**

      Transformer-based detectors (e.g., DETR families)

      Lightweight models for edge devices (NVIDIA Jetson, Raspberry Pi, mobile AI chips)

      Multi-class + multi-object tracking (MOT)

**3. Traffic Behavior Understanding**

      Illegal lane-changing detection

      Red-light violation detection

      Accident risk prediction using trajectory analysis

      Behaviour classification using temporal deep learning models (LSTM, TCN)

**4. High-Level Transportation Research**

      Statistical traffic flow modelling

      Automated urban planning analysis

      Integration with GIS data

      Predictive modelling for future traffic demand

**5. Smart-City and IoT Integration**

      Connecting the system to cloud dashboards

      Large-scale distributed traffic monitoring

      Low-power embedded deployments

      Intelligent traffic control systems

      Real-World Applications

**This type of system is commonly used in**

      Highway monitoring systems

      Smart city surveillance networks

      Urban traffic control centers

      Toll booth automation

      Intelligent parking systems

      Public transportation scheduling

These applications are widely deployed by transportation authorities, road-safety agencies, and smart-city companies around the world.


**🧠 Installation & Setup**

**Step 1**

Download the source code and open the project folder in PyCharm.

**Step 2**

Go to Terminal and install the following packages:


      pip install absl-py attrs backcall  cachetools certify charset-normalizer click cmake Colorama cvzone cycler Cython decorator filterpy flatbuffers fonttools future geographiclib geopy google-auth google-auth-oauthlib greenlet grpcio idna imageio importlib-metadata ipython iso8601 itsdangerous jedi joblib kivy deps.angle kivy-deps.glew kivy-deps.sdl2 kiwisolver Markdown MarkupSafe matplotlib matplotlib-inline MouseInfo network network numpy oauthlib opencv-python packaging pandas parso phonenumbers pickleshare Pillow prompt-toolkit protobuf psutil pyasn1 pyasn1-modules PyAudio PyAutoGUI pycocotools-windows PyGetWindow Pygments PyMsgBox pyparsing pyperclip pypiwin32 PyRect PyScreeze pyserial python-dateutil pytweening pytz PyWavelets pywin32 PyYAML pyzbar requests requests-oauthlib rsa scikit-image scikit-learn scipy seaborn sentry-sdk serial six sklearn tensorboard tensorboard-data-server tensorboard-plugin-wit thop threadpoolctl tifffile torch torchvision torchvision-detection tqdm traitlets typing_extensions ultralytics urllib3 vidstream wcwidth Werkzeug zipp


**Step 3**

Now just run the program — and you’re done! ✅


**Output:**

<img width="1365" height="725" alt="Screenshot_1" src="https://github.com/user-attachments/assets/f5788d09-22b4-4408-ae0c-aec3f5c7e692" />
<img width="1365" height="729" alt="Screenshot_2" src="https://github.com/user-attachments/assets/19edb57f-76b1-4457-98db-f22583d5dfea" />
<img width="1358" height="725" alt="Screenshot_3" src="https://github.com/user-attachments/assets/8e3833bd-22f5-486a-b648-898421d78271" />
<img width="1365" height="727" alt="Screenshot_4" src="https://github.com/user-attachments/assets/d229d4b2-8698-4bee-b067-2ebc1d1fd92b" />



**📬 Contact**

If you face any problems, feel free to reach out:

Facebook: https://www.facebook.com/arafathosense

Email: arafat.bd.hosen@gmail.com

**WhatsApp: +8801744805068**

**WeChat: arafat_cn**

**QQ: 3522584423**
