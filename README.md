# Kumpas

KUMPAS: 3D Animated Speech-to-Sign Language Avatar Translator Mobile Application for the Deaf Community Using Whisper and DeBERTa-v3
KUMPAS is a mobile application developed as a thesis project with the goal of promoting inclusivity and bridging communication gaps for the Deaf and Hard of Hearing community. The system translates speech or text into sign language animations (FSL and ASL) using state-of-the-art AI technologies, supporting both Filipino and English, with limited dialect flexibility.

🔧 Key Features
🎙 Multi-Modal Input Support
Accepts both voice and text input for flexible translation.

🌐 Multi-Language Processing
Supports English, Tagalog, and Cebuano input. Other dialects (e.g., Waray, Ilocano) are not officially supported but are not strictly rejected due to missing language validation.

🧠 Sentiment Analysis Toggle
Enhances avatar emotion based on input sentiment (e.g., sad, happy) using a switchable NLP setting.

✋ Sign Language Output
Converts recognized speech or typed text into animated Filipino Sign Language (FSL) or American Sign Language (ASL) using a 3D avatar system.

📦 Fallback Handling
Words not found in the dictionary are automatically spelled out using fingerspelling animation.

⚠️ Censorship Filter
Detects and blocks profane or inappropriate language.

🧪 Error Handling
Catches invalid or empty inputs and alerts the user, although some edge cases (e.g., unsupported languages) still need improvement.

🛠️ Tech Stack
Frontend: Android Studio (Java)

Backend: Flask (Python)

Database: Firebase Realtime Database

Animation Engine: PoseFormat-based 3D avatar rendering for sign language videos

Cloud APIs: Google Cloud Speech-to-Text & Translation API

🤖 Machine Learning / NLP Models Used

🗣 Whisper (by OpenAI)
Purpose: Speech-to-text transcription
Role in System: Converts user-recorded speech into translatable text

🧠 DeBERTa v3
Purpose: Language understanding and dialect classification
Role in System: Extracts contextual meaning and aids translation to appropriate sign language gesture equivalents

