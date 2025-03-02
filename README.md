# AI-Task-Optimizer
Employee AI Task Optimizer is an intelligent system that analyzes employees' emotions through text, facial expressions, and speech to recommend the most suitable tasks. The goal is to enhance work productivity, mental well-being, and stress management in workplaces.
This project integrates Natural Language Processing (NLP), Computer Vision, and Speech Emotion Recognition to detect moods and dynamically suggest tasks that align with an employee’s emotional state.

![Face recognition](https://github.com/user-attachments/assets/75c3d2be-e44e-4c02-b7cd-040769f90ea5)

📌 Key Features:
✅ Text-Based Emotion Analysis – Uses DistilBERT to classify emotions from text input.

✅ Facial Expression Detection – Uses DeepFace to analyze facial expressions in real-time.

✅ Speech Emotion Recognition – Uses Wav2Vec2 to classify emotions from voice recordings.

✅ Task Recommendation System – Maps detected emotions to relevant work tasks.

✅ Real-Time Processing – Provides instant feedback for productivity enhancement.






📌 Installation & Usage:

1️⃣ Clone the Repository

2️⃣ Install Dependencies

    pip install -r requirements.txt
    
3️⃣ Run the Application

    streamlit run app.py



    

    
📌 Technologies Used:

Python  (Core Development)

Streamlit  (Frontend UI)

Transformers (Hugging Face)  (NLP & Speech Emotion Recognition)

DeepFace  (Facial Expression Analysis)

Librosa  (Audio Processing)

OpenCV  (Webcam Image Capture)

Kafka (Optional)  (For real-time streaming if needed)





📌 How It Works:

1️⃣ User Inputs Emotion Data – via text, webcam, or microphone.

2️⃣ AI Models Detect Emotion – using NLP, facial analysis, and speech recognition.

3️⃣ Task Recommendation – The system suggests a task based on detected emotion.

4️⃣ Employee Adjusts Work Tasks Accordingly – leading to better productivity and stress management.





📌 Future Enhancements:

🚀 Improving emotion classification accuracy with larger datasets.

🚀 Adding stress-level monitoring over time for better HR intervention.

🚀 Integrating voice-based task automation (e.g., suggest tasks via voice commands).




