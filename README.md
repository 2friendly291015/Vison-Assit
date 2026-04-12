# Real-Time Vision Assist

## Project Overview
Real-Time Vision Assist is an AI-powered assistive system designed to help visually impaired individuals understand their surroundings through real-time audio feedback.

This project has been developed as a **3rd Semester Mini Project for the Master of Computer Applications (MCA)**.

The system captures live video input, processes it using computer vision and deep learning techniques, and converts detected objects into speech output.

---

## Objectives
- Assist visually impaired individuals in identifying objects  
- Provide real-time audio feedback using Text-to-Speech (TTS)  
- Apply Artificial Intelligence and Computer Vision in real-world scenarios  
- Develop a cost-effective and user-friendly assistive system  

---

## Technologies Used
- Programming Language: Python  
- Computer Vision: OpenCV  
- Machine Learning: TensorFlow / CNN  
- Text-to-Speech: gTTS / pyttsx3  
- Libraries: NumPy, Pillow  

---

## System Working
1. Capture real-time video using a webcam  
2. Process frames using a trained CNN model  
3. Detect objects in the video stream  
4. Generate descriptive output (e.g., "I can see a chair")  
5. Convert text into speech output 
real-time-vision-assist/
│
├── main.py
├── requirements.txt
├── model/
├── utils/
│ ├── detection.py
│ └── speech.py
├── assets/
├── docs/
└── README.md


---

## Installation and Setup

### Step 1: Clone the Repository

git clone https://github.com/your-username/real-time-vision-assist.git

cd real-time-vision-assist


### Step 2: Install Dependencies

pip install -r requirements.txt


### Step 3: Run the Application

python main.py


---

## Output Example

"I can see a chair"
"I can see a person"

---

## Advantages
- Improves independence for visually impaired users  
- Provides real-time environmental awareness  
- Simple, lightweight, and cost-effective solution  

---

## Limitations
- Performance depends on lighting conditions  
- Limited object detection categories  
- Accuracy may vary in complex environments  

---

## Future Enhancements
- Integration with mobile applications (Android/iOS)  
- Implementation of advanced models like YOLO  
- GPS-based navigation assistance  

---

## Academic Details
- Course: Master of Computer Applications (MCA)  
- Semester: 3rd Semester  
- Project Type: Mini Project  
- Project Title: Real-Time Vision Assist  

---

## Contributors
- Nalini Srivastava  
- Amarjit L Singh  

---

## License
This project is licensed under the MIT License.

---

## Acknowledgement
This project was developed as part of MCA coursework and demonstrates the practical application of Artificial Intelligence and Computer Vision in solving real-world accessibility challenges.

---

## Project Structure
