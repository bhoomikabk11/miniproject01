# Setup
1. python -m venv venv
2. source venv/bin/activate  # or venv\Scripts\activate on Windows
3. pip install -r requirements.txt
4. python manage.py migrate
5. python manage.py createsuperuser
6. python manage.py runserver

Open http://127.0.0.1:8000/ and register/login.

Notes:
- For webcam monitoring, serve the site over https or in localhost (Chrome allows getUserMedia on localhost).
- If you prefer server-side TTS, integrate e.g. gTTS or a TTS API; current implementation uses browser SpeechSynthesis.