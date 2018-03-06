# django-twiliochat
A Django based chat app powered by Twilio.

To get to minimum viable product:

1. Copy env.txt to .env and populate it with Twilio API values for:
    - Twilio Account SID
    - Chat SID
    - Sync SID
    - API SID
    - API Key
2. Install the Python libraries with `pip install -r requirements.txt`.
3. Start the application with `honcho run ./manage.py runserver`.
4. Open a browser and surf to http://127.0.0.1:8000
