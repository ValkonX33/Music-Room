Music Room



Music Room is a web application that allows users to create a virtual room where they can listen to music together using the Spotify API. It provides a collaborative music experience where users can vote to skip songs, and when the votes to skip limit is reached, the current song is automatically skipped.

Technologies Used-
React.js
Django
Material UI
Spotify API

Features-
User registration and authentication
Creating and joining music rooms
Displaying the current song information
Voting to skip songs
Automatic song skipping when the votes to skip limit is reached
Host user controls to modify the votes to skip limit


Getting Started
To get started with Music Room, follow these steps:

Clone the repository:

![image](https://github.com/ValkonX33/Music-Room/assets/77388132/c7d3554b-156f-4550-8028-26a5678207e6)

Change into the project directory:
![image](https://github.com/ValkonX33/Music-Room/assets/77388132/0753b5de-5655-4ca7-a5d3-077b10f331b0)

Install the frontend dependencies:

![image](https://github.com/ValkonX33/Music-Room/assets/77388132/c6cad8ea-3ec9-4100-9545-1e70ab1e0093)

Install the backend dependencies:

![image](https://github.com/ValkonX33/Music-Room/assets/77388132/36caae14-09e0-4b0c-8db5-818bfa22d7bd)

Create a Spotify developer account and obtain the necessary API credentials. Update the backend configuration file (backend/settings.py) with your Spotify API credentials.

Run the backend server:

![image](https://github.com/ValkonX33/Music-Room/assets/77388132/d40d3ffe-82ca-4a1b-bd29-877ba4d013dd)

Run the frontend development server:

![image](https://github.com/ValkonX33/Music-Room/assets/77388132/3951846c-d557-40d4-86d5-2422b8467379)

Open your web browser and visit http://localhost:3000 to access the Music Room application.

Configuration
Backend Configuration
The backend configuration file is located at backend/settings.py. Update the following variables with your Spotify API credentials:


![image](https://github.com/ValkonX33/Music-Room/assets/77388132/8c6e703f-7281-49fa-a340-a34a5a1b5861)

Frontend Configuration
The frontend configuration file is located at frontend/src/config.js. Update the following variable with the backend API URL:

![image](https://github.com/ValkonX33/Music-Room/assets/77388132/7218f678-112e-47ec-ae0d-866a05bc1c30)

Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

License
This project is licensed under the MIT License.
