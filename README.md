🐾 CatCare AI
Multi-Modal Feline Emotion Detection & Pet Management System

CatCare AI is a full-stack intelligent platform designed to interpret feline emotions and improve pet care using AI. It combines Computer Vision, Acoustic Deep Learning, and LLM-based validation to deliver a comprehensive understanding of a cat’s well-being.

Developed as part of Virtual Internship 6.0 (2026).

🌟 Overview

CatCare AI goes beyond basic detection by integrating multiple AI modalities into a single ecosystem.

Key Capabilities
Multi-modal emotion detection (image + audio)
AI-powered validation using Gemini
Full pet lifecycle management system
Real-time monitoring and alerts
Social and community interaction features
🛠️ Tech Stack
🔹 Backend & AI Engine
Framework: Django 4.2.7 (REST Framework 3.16.1)
Deep Learning: TensorFlow 2.18.0
Audio Processing: Librosa 0.10.1
Computer Vision: OpenCV, Pillow
Validation: Google Gemini API
Database: PostgreSQL (Production), SQLite (Development)
🔹 Frontend & UI
Design: Mobile-first responsive UI
Framework: Bootstrap 5, Custom CSS
Interactivity: AJAX-based JavaScript
Icons: Font Awesome
🧠 Machine Learning Models
🖼️ Image Emotion Detection (CNN)
Input: 224 × 224 RGB images
Model: best_cat_emotion_model.keras
Classes:
Angry
Disgusted
Happy
Normal
Sad
Scared
Surprised
🔊 Audio Emotion Detection (DNN)
Input: .wav, .mp3 files
Feature Extraction: MFCC, Spectral Centroid
Model: advanced_cat_model_80.h5
Classes:
Angry, Defence, Fighting
Happy, HuntingMind, Mating
MotherCall, Paining
Resting, Warning
🚀 Core Features
📸 AI-Powered Detection
Real-time emotion classification with confidence scores
Audio-based emotion recognition using spectral features
Gemini API validation ensures only cat-related data is processed
🏥 Health & Monitoring
Smart alerts for abnormal emotional patterns
Cat profile management (weight, vaccination, medical history)
Medication reminders
Emotion trend analytics with dashboards
🤝 Community & Interaction
Social feed for sharing pet updates
Like, comment, and engage with other users
Real-time chat system (WhatsApp-style UI)
AI assistant for pet care guidance
guidance
📊 Dashboard Preview
Emotion Trends & Insights
The dashboard provides:
<img width="1920" height="1080" alt="Screenshot (269)" src="https://github.com/user-attachments/assets/c3e59acb-dfed-419f-8726-1d8939f3440e" />
<img width="1920" height="1080" alt="Screenshot (268)" src="https://github.com/user-attachments/assets/0a3bb60b-497d-470c-9cf9-21af754203ec" />
<img width="1920" height="1080" alt="Screenshot (267)" src="https://github.com/user-attachments/assets/c31ea6bc-8050-42d5-8233-00e76d14cd69" />
<img width="1920" height="1080" alt="Screenshot (266)" src="https://github.com/user-attachments/assets/2131c4af-1c23-44d6-9182-d25fe5dce436" />
<img width="1920" height="1080" alt="Screenshot (265)" src="https://github.com/user-attachments/assets/c71dca26-c515-497a-9753-f49bb187aa2d" />
Emotion distribution (pie/radar charts)
Historical mood trends
Unified media gallery from detection + social posts
⚙️ Installation & Setup
1. Clone Repository
git clone https://github.com/your-username/catcare-ai.git
cd catcare-ai
2. Install Dependencies
pip install -r requirements.txt
3. Configure Environment Variables

Create a .env file in the root directory:

GEMINI_API_KEY=your_google_gemini_key
GOOGLE_OAUTH_CLIENT_ID=your_id
GOOGLE_OAUTH_SECRET=your_secret
SECRET_KEY=your_django_secret_key
4. Run the Project
python manage.py migrate
python manage.py runserver
🛡️ Disclaimer

CatCare AI is an assistive system and should not be used as a substitute for professional veterinary advice. Always consult a licensed veterinarian for medical decisions.

👩‍💻 Author

Pujitha K

AI & ML Engineer
Virtual Internship 6.0 (2026)
⭐ Future Improvements
Mobile app integration
Wearable IoT device support for pets
Advanced behavioral prediction using time-series models
Multilingual AI assistant
