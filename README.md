ChatApp
ChatApp is a simple web-based chat application built using Django, HTML, CSS, and Python. It allows users to create accounts, join chat rooms, and communicate with other users in real-time.

Features
User Authentication: Users can sign up for an account and log in securely.
Real-time Chat: Users can join chat rooms and communicate with other users in real-time.
Multiple Rooms: ChatApp supports multiple chat rooms, allowing users to create new rooms or join existing ones.
Responsive Design: The application is designed to be responsive and work seamlessly across different devices and screen sizes.
Installation
To run ChatApp locally, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/chatapp.git
Navigate to the project directory:
bash
Copy code
cd chatapp
Install the dependencies:
Copy code
pip install -r requirements.txt
Apply database migrations:
Copy code
python manage.py migrate
Start the development server:
Copy code
python manage.py runserver
Open your web browser and visit http://localhost:8000 to access the application.
Usage
Sign up for a new account or log in if you already have an account.
Once logged in, you'll see a list of available chat rooms. You can either join an existing room or create a new one.
Inside a chat room, you can send messages in real-time and see messages from other users.
You can also customize your profile by uploading a profile picture and setting a status message.
