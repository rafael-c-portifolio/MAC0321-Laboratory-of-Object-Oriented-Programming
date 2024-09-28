# MAC0321-Laboratory-of-Object-Oriented-Programming
Group Playlist Organizer Using Spotify API - MAC0321 Laboratory of Object Oriented Programming
This project was completed as part of the MAC0321 - Laboratory of Object Oriented Programming course. The objective was to develop a simple application using the Spotify API. Our group chose to create a Group Playlist Organizer that suggests new songs for playlists based on the tastes of each group member. The application was developed using JavaScript, HTML, and CSS.

Project Overview
The Group Playlist Organizer is a web-based application that allows users to manage and enhance their collaborative Spotify playlists. The key feature is that it suggests new songs for the playlist by analyzing the musical preferences of all group members. The application leverages data provided by the Spotify API to deliver personalized recommendations.

Features:
Spotify API Integration: The application interacts with Spotify’s API to fetch user data, including playlists, liked songs, and listening habits.
User Taste Analysis: Using data such as favorite genres, artists, and tracks, the app compares the musical tastes of each group member.
Song Recommendations: The application suggests new songs that could fit well into the group playlist, based on the combined tastes of all users.
Playlist Management: Users can view, edit, and manage their playlists directly through the app.
Technologies Used
JavaScript: The core logic for interacting with the Spotify API, analyzing user data, and generating song recommendations was implemented in JavaScript.
HTML & CSS: The frontend design and structure of the application were created using HTML and CSS, ensuring a responsive and user-friendly interface.
Spotify API: Spotify’s Web API was used to retrieve user information such as playlists, track details, and audio features.
Design Process
1. Spotify API Integration
We first authenticated users via the Spotify API, allowing access to their playlists and favorite songs.
Once authenticated, the API provided access to key data such as user profile information, playlists, and audio features for tracks (e.g., tempo, energy, and danceability).
2. User Taste Analysis
We analyzed the audio features of each user's top tracks and playlists using the data fetched from Spotify. This data was used to identify patterns in genres, artists, and songs that the user preferred.
A similarity algorithm was developed to find common ground between the musical preferences of all group members.
3. Song Recommendation System
Based on the user taste analysis, the app generated song recommendations by querying Spotify’s song database for tracks that matched the group's collective tastes.
Recommended songs were displayed to users, who could choose to add them to the playlist directly from the app.
4. Frontend Design
The frontend was designed using HTML and CSS to provide an intuitive interface where users could view the playlists, suggested songs, and add them to the playlist with just a few clicks.
Challenges and Learning Outcomes
API Integration: Understanding and working with the Spotify API was challenging but rewarding. We had to carefully manage API requests, handle authentication tokens, and ensure data was correctly fetched and processed.

User Data Processing: Designing the recommendation algorithm to analyze user tastes and provide relevant song suggestions required careful consideration of Spotify’s audio features and a deep understanding of data structures in JavaScript.

Collaborative Development: Working as a group to develop an application that integrated frontend and backend functionality using JavaScript, HTML, and CSS helped reinforce collaborative coding and version control practices.
