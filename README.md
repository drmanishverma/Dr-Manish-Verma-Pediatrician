Firebase Cloud Functions - Vaccination Reminder

1. Install dependencies:
   cd functions
   npm install

2. Authenticate and initialize firebase in your environment:
   firebase login
   firebase init functions

3. Set your SMS API key securely:
   firebase functions:config:set sms.apikey="YOUR_API_KEY"

4. Deploy functions:
   firebase deploy --only functions
