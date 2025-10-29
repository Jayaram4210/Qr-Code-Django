Project Title: Django QR Menu Generator

Description: This is a Django-powered web application that allows restaurants to generate QR codes for their digital menus. It uses Python’s qrcode library and Bootstrap for a clean, mobile-friendly interface. The app lets users input a restaurant name and menu URL, then generates a downloadable QR code image. It’s designed to help restaurants offer hygienic, contactless menus in a modern way.

Tech Stack:-
Django
Python
Bootstrap
qrcode
Pillow
PostgreSQL

Installation Instructions:-
1. Clone the repository: git clone https://github.com/Jayaram4210/Qr-Code-Django.git cd Qr-Code-Django

2. Create a virtual environment: python -m venv venv On
   - Windows: venv\Scripts\activate
   - On Mac/Linux: source venv/bin/activate

3. Install dependencies: pip install -r requirements.txt

4. Run the server: python manage.py runserver

5. Open your browser and go to: http://127.0.0.1:8000/



Features:-

Input restaurant name and menu URL

Generate QR code image

Preview and download QR code

Mobile-friendly Bootstrap UI



Troubleshooting:-

Make sure the media/ folder exists and is writable

Check settings.py for correct MEDIA_ROOT and MEDIA_URL

Use python manage.py collectstatic if deploying to production

Ensure all required packages are listed in requirements.txt


Author:-
Chintala Jayaram Bhavani Prasad
GitHub: https://github.com/Jayaram4210
