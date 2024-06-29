# IARE_prep_Bot
IARE_Exam_Prep_Bot/
│
├── config.py
├── bot.py
├── handlers/
│   ├── __init__.py
│   ├── file_handler.py
│   ├── text_handler.py
│   ├── voice_handler.py
│   ├── payment_handler.py
│   ├── search_handler.py
├── requirements.txt
├── utils/
│   ├── __init__.py
│   ├── file_utils.py
│   ├── text_extraction.py
│   ├── speech_recognition.py
│   ├── database.py
│   ├── cleanup.py  # Script to delete old user-uploaded files (every 48 hours)
├── README.md
├── voice/
│   └── (voice files stored here, deleted every 48 hours)
└── study_material/
    └── (uploaded study material stored here, not deleted automatically)
