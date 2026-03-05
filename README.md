# VoxEmotion – Speech Emotion Detection using Python

## Project Description
VoxEmotion is a Speech Emotion Detection system developed using Python.  
The system records voice input or accepts an audio file, converts the speech into text using speech recognition, and analyzes the emotional sentiment of the spoken content using Natural Language Processing (NLP).

This project uses sentiment analysis techniques to identify whether the spoken content expresses **positive, negative, or neutral emotion**.

The system also includes a **login authentication module using MySQL** and a **Tkinter graphical user interface (GUI)** for interaction.

---

## Objectives
- Record voice input from the user
- Convert speech to text
- Analyze sentiment using NLP
- Identify emotion from speech
- Provide a simple graphical interface
- Secure login authentication using MySQL

---

## Technologies Used

| Technology | Purpose |
|-------------|-------------|
| Python | Main programming language |
| Tkinter | GUI development |
| MySQL | User authentication database |
| SpeechRecognition | Convert speech to text |
| NLTK | Sentiment analysis |
| SoundDevice | Voice recording |
| SoundFile | Audio file processing |
| SciPy | Audio file saving |

---

##  Project Structure
VoxEmotion-Speech-Emotion-Detection/
│
├── login.py              # Login window with MySQL authentication
├── Admin.py              # Main application interface (record voice & detect emotion)
├── database.sql          # MySQL database file for login table
├── out.wav               # Recorded audio file (generated after recording)
├── new.wav               # Processed audio file
├── requirements.txt      # Python libraries required for the project
└── README.md             # Project documentation
