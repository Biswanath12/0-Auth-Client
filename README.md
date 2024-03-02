# Authlib Connect

Authlib Connect is a simple Flask web application that demonstrates the integration of OAuth authentication with Google, Twitter, and Facebook.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [How it Works](#how-it-works)
- [License](#license)

## Prerequisites
Make sure you have the following installed on your system:
- Python (version 3.x)
- Flask
- Authlib

You can install the required packages using the following command:

pip install Flask Authlib

Installation
    1. Clone the repository
       git clone https://github.com/your-username/authlib-connect.git
       cd authlib-connect
    2. Install the dependencies:
       pip install -r requirements.txt
Configuration
    1. Set up OAuth applications on the respective platforms (Google, Twitter, Facebook) and obtain the client ID and client secret.
    2. Set the environment variables for the client IDs and secrets:
       export GOOGLE_CLIENT_ID="your_google_client_id"
       export GOOGLE_CLIENT_SECRET="your_google_client_secret"
       export TWITTER_CLIENT_ID="your_twitter_client_id"
       export TWITTER_CLIENT_SECRET="your_twitter_client_secret"
       export FACEBOOK_CLIENT_ID="your_facebook_client_id"
       export FACEBOOK_CLIENT_SECRET="your_facebook_client_secret"

Usage
Run the Flask Application:
python app.py
Visit http://localhost:5000 in your web browser.
How it works
        ? The main entry point of the application is app.py.
        ? The application uses Flask and Authlib to handle OAuth authentication with Google, Twitter, and Facebook. 
        ? Each provider (Google, Twitter, Facebook) has its route (/google/, /twitter/, /facebook/) for initiating the authentication process. 
        ? After authentication, user details are printed to the console. Modify the code as needed to store or process the user information. 
        ? The application also includes a simple HTML page (index.html) to display the authentication buttons. 
Licence
This project is licensed under the MIT License.
	

