
Music Room
Music Room is a web application that allows users to create a virtual room where they can listen to music together using the Spotify API. It provides a collaborative music experience where users can vote to skip songs, and when the votes to skip limit is reached, the current song is automatically skipped.

Technologies Used
React.js
Django
Material UI
Spotify API
Features
User registration and authentication
Creating and joining music rooms
Displaying the current song information
Voting to skip songs
Automatic song skipping when the votes to skip limit is reached
Host user controls to modify the votes to skip limit
Getting Started
To get started with Music Room, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/music-room.git
Change into the project directory:

bash
Copy code
cd music-room
Install the frontend dependencies:

bash
Copy code
cd frontend
npm install
Install the backend dependencies:

bash
Copy code
cd ../backend
pip install -r requirements.txt
Create a Spotify developer account and obtain the necessary API credentials. Update the backend configuration file (backend/settings.py) with your Spotify API credentials.

Run the backend server:

bash
Copy code
python manage.py runserver
Run the frontend development server:

bash
Copy code
cd ../frontend
npm start
Open your web browser and visit http://localhost:3000 to access the Music Room application.

Configuration
Backend Configuration
The backend configuration file is located at backend/settings.py. Update the following variables with your Spotify API credentials:

python
Copy code
SPOTIFY_CLIENT_ID = 'your-client-id'
SPOTIFY_CLIENT_SECRET = 'your-client-secret'
Frontend Configuration
The frontend configuration file is located at frontend/src/config.js. Update the following variable with the backend API URL:

javascript
Copy code
export const API_URL = 'http://localhost:8000/api';
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

License
This project is licensed under the MIT License.
