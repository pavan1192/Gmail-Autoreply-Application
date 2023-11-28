# Gmail Autoreply Application
  This Node.js app automates vacation email responses for a Gmail account. It checks for new emails, sends replies to first-time threads, adds a label, and repeats the process randomly every 45 to 120 seconds. Authentication is handled through the "Login with Google" API, utilizing Google's Gmail API for seamless interactions.

# Features

- Node.js clusters support.
- Checks for new emails in a given Gmail ID.
- Sends replies to emails that have no prior replies.
- Adds a label to the email and moves the email to the label.
- This app checks above steps every 45 to 120 in b/w sec  random time interval.

# Prerequisites

- Node.js installed on your machine.
- Google Cloud Console project set up with the Gmail API enabled.
- OAuth2 credentials obtained from the Google Cloud Console.
- credentials.js file with the following details:
  - CLIENT_ID
  - CLIENT_SECRET
  - REDIRECT_URI
  - REFRESH_TOKEN
  - Installation
