Introduction
This project aims to automate reply on chat

Prerequisites
Before running the application, make sure you have the following:

Node.js installed on your machine
Google Cloud Platform project with the Gmail API enabled
Google API credentials in JSON format
A valid API key for Google's Generative AI
Installation
Clone the repository:
git clone <repository_url>
Install dependencies:
npm install
Set up environment variables:
Create a .env file in the project root directory and add the following:

GEMINI_API_KEY=<your_google_api_key>
Replace <your_google_api_key> with your actual Google API key.

Usage
To start the server, run:

npm start
Endpoints
/login: Redirects to Google login consent screen for OAuth2 authentication.
/auth/google/callback: Handles Google's redirect after user login.
/emails: Fetches emails, processes them using AI, and sends automated replies.
Contributing
Contributions are welcome! Please read the contributing guidelines before getting started.

License
#   C h a t - b o t  
 #   C h a t - b o t  
 