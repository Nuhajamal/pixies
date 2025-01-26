**HOSTED PROJECT LINK**  
https://github.com/Nuhajamal/pixie

**PROJECT DESCRIPTION**  
This project integrates face recognition into a CCTV system for real-time monitoring and automated attendance tracking. It simplifies surveillance by identifying individuals in live video streams and logging their attendance efficiently.

**THE PROBLEM STATEMENT**  
Manually tracking attendance or identifying individuals from CCTV footage is tedious and error-prone, especially in large-scale setups.

**THE SOLUTION**  
By harnessing face recognition and computer vision, this system automates real-time identification and attendance logging. It’s fast, accurate, and ensures seamless monitoring.

**TECHNICAL DETAILS**  
**FOR SOFTWARE:**  

**LANGUAGES USED:** Python  
**FRAMEWORKS USED:** tkinter (for GUI development)  
**LIBRARIES USED:**  
> face_recognition  
> OpenCV  
> PIL  
> NumPy  

**TOOLS USED:**  
- Visual Studio Code (IDE)  
- Python Virtual Environment  

**FOR HARDWARE:**  
- Webcam (for live video feed)  

**IMPLEMENTATION:**  

**FOR SOFTWARE:**  

**INSTALLATION:**  
`pip install face_recognition opencv-python numpy pillow`  

**RUN:**  
`python final.py`  
Start face recognition by clicking the "Face Recognition Live" button.

**SCREENSHOTS:**  
1. **INTERFACE:**  
![INTERFACE](https://github.com/user-attachments/assets/1a9d7b78-f3a0-4399-a2cd-df27b8c7d147)
The first screenshot shows the graphical user interface (GUI) of the project. It features a sleek design with a background image, a prominent title at the top, and a "Face Recognition Live" button that allows the user to start the face recognition process. The button is accompanied by a related icon for clarity. The overall layout is clean and user-friendly, designed with a modern look for efficient navigation.

2. **FACE RECOGNITION IN ACTION:**  
![FACE RECOGNITION](https://github.com/user-attachments/assets/ca1944fe-72af-4fdb-9627-3dd2c9d1f8fb)
The second screenshot displays the face recognition feature in action. It shows the live video stream captured by the webcam. As individuals appear in front of the camera, the system detects and highlights their faces with a green box. The detected person's name is displayed above their face, indicating that the system has successfully identified them. The image demonstrates how the system continuously scans for faces and performs real-time identification, making it efficient for surveillance and attendance tracking.

3. **ATTENDANCE CSV FILE:**  
![CSV FILE](https://github.com/user-attachments/assets/87350d04-0664-407e-bd69-3afcb5842745)
The third screenshot shows the attendance data saved in a CSV file. Each entry records the detected individual's name, the current date, and the time they were identified. This file is automatically updated each time a face is recognized, making it easy to track attendance in real time. The CSV format ensures that the data is easily accessible and can be processed further, such as for generating reports or performing analysis

**DIAGRAMS:**  
![Screenshot 2025-01-26 102304](https://github.com/user-attachments/assets/f5b9042e-2339-4d4a-bece-b3ab4503e0f0)

**TEAM CONTRIBUTIONS**  
**NUHA JAMAL:** Developed the frontend GUI and managed the project, Handled testing and debugging.  
**FATHIMA NAJA:** Implemented backend face recognition and encoding logic.
