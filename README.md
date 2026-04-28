## 🇬🇧 English Version
# Real-Time Face Recognition System (Advanced Version)
This project is an advanced face recognition system using a Raspberry Pi camera, OpenCV, and the face_recognition library.

It detects faces in real time, compares them with a reference image, and identifies known or unknown persons.

# Features
- Real-time camera streaming
- Face detection using OpenCV (Haar Cascade)
- AI-based face recognition using face_recognition library
- Comparison with reference image
- Display of name and recognition confidence
- Bounding boxes and labels on detected faces
- Live video display

# How it works
- The camera captures video frames continuously
- OpenCV detects face locations
- Detected faces are cropped
- face_recognition generates face encodings
- Encodings are compared with a reference image
- Result is displayed:
  - 🟢 Known person
  - 🔴 Unknown person

# Requirements
- Python 3.x
- Raspberry Pi with camera
- OpenCV (cv2)
- face_recognition
- numpy
- picamera2
- Haarcascade file: `haarcascade_frontalface_default.xml`

# Installation
pip install opencv-python face-recognition numpy picamera2

# Run the program
python v2_advanced_recognition.py

Exit the program by pressing:
q

# Author
M. Yilmaz

---------------------------------------------------------------------------------------------------------------------------
## 🇩🇪 German Version
## Echtzeit-Gesichtserkennung mit Python (Advanced Version)

Dieses Projekt ist eine erweiterte Version einer einfachen Gesichtserkennung.  
Es verwendet eine Raspberry Pi Kamera sowie OpenCV und die face_recognition Library, um Gesichter in Echtzeit zu erkennen und mit einem Referenzbild zu vergleichen.


## Features
- Echtzeit-Kameraübertragung  
- Gesichtserkennung mit OpenCV (Haar Cascade)  
- KI-basierte Gesichtserkennung mit face_recognition  
- Vergleich mit Referenzbild  
- Anzeige von Name und Erkennungswahrscheinlichkeit  
- Markierung erkannter Gesichter im Bild (Rahmen + Text)  
- Live-Videoanzeige  


## Funktionsweise
1. Die Kamera nimmt kontinuierlich Bilder in Echtzeit auf  
2. Gesichter werden zuerst mit OpenCV lokalisiert  
3. Der erkannte Bereich wird ausgeschnitten  
4. Mit face_recognition wird ein Encoding erstellt  
5. Dieses Encoding wird mit einem Referenzbild verglichen  
6. Ergebnis wird angezeigt:
   - 🟢 Bekannte Person  
   - 🔴 Unbekannte Person  


## Voraussetzungen
- Python 3.x  
- Raspberry Pi mit Kamera  
- OpenCV (cv2) 
- face_recognition  
- numpy  
- picamera2
- Haarcascade file: `haarcascade_frontalface_default.xml`


## Installation
pip install opencv-python face-recognition numpy picamera2

##Starten des Programms: 
python v2_advanced_recognition.py


##Beenden mit Taste:
q

##Autor
M. Yilmaz

