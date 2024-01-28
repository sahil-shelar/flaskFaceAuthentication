
Face Recognition Web App
This project is a simple web application for face recognition using Flask, OpenCV, and face_recognition library. Users can register their face by capturing a photo through their webcam and subsequently use it to log in.

Getting Started
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/face-recognition-web-app.git
cd face-recognition-web-app
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Flask application:

bash
Copy code
python app.py
Open your web browser and navigate to http://localhost:5000.

Usage
Registration:
Enter your name in the provided input field.
Allow the web application to access your webcam.
Click the "Capture Photo" button to capture your face.
Click the "Register" button to register your face.
Login:
Enter your name in the provided input field.
Allow the web application to access your webcam.
Click the "Capture Photo" button to capture your face.
Click the "Login" button to log in.
Success:
If the login is successful, you will be redirected to a success page with your name.

Project Structure
app.py: Flask application file containing server-side code.
static/: Static assets including CSS, JavaScript, and uploaded images.
templates/: HTML templates used by Flask for rendering pages.
JavaScript File (js/script.js)
This file contains client-side JavaScript code to interact with the webcam, capture photos, and communicate with the server for registration and login.

Notes
Face detection is performed using Haar Cascades.
Face recognition is implemented using the face_recognition library.
Registered data is stored in-memory for demonstration purposes. In a real-world scenario, a database should be used.
Dependencies
Flask
OpenCV
face_recognition
Acknowledgments
This project is inspired by various tutorials and resources on face recognition and web development. Special thanks to the Flask and OpenCV communities.

Feel free to contribute, report issues, or suggest improvements!





