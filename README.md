# Gmail Autoreply Application
  This Node.js app automates vacation email responses for a Gmail account. It checks for new emails, sends replies to first-time threads, adds a label, and repeats the process randomly every 45 to 120 seconds. Authentication is handled through the "Login with Google" API, utilizing Google's Gmail API for seamless interactions.

# Features

1.Node.js clusters support.
2.Checks for new emails in a given Gmail ID.
Sends replies to emails that have no prior replies.
Adds a label to the email and moves the email to the label.
This app checks above steps every 45 to 120 in b/w sec random time interval.
