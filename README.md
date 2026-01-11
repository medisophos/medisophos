Smart Medicine Management System using QR Code

Requirements:
- Python 3.10+
- pip

Install dependencies:
    pip install -r requirements.txt

Run:
    python app.py

Open in browser: http://127.0.0.1:5000

Project structure (single-folder):
medicine_qr_project/
├── app.py
├── requirements.txt
├── README.md
├── templates/
│   ├── index.html
│   ├── dashboard.html
│   ├── add_medicine.html
│   ├── view_medicine.html
│   └── update_medicine.html
└── static/
    ├── css/
    │   └── style.css
    └── qr_codes/  # auto-created at runtime

Notes:
- This is a minimal, extendable starter. It uses SQLite for simplicity.
- For production use: add authentication, validation, input sanitation, HTTPS, and role-based access.
