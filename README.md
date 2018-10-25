# Send SMS with React

This is an example of sending SMS using React and Twilio. 

It consists of a `SMSForm` component that communicates with a server endpoint to [send SMS messages via the Twilio REST API](https://www.twilio.com/docs/sms/send-messages).

## Running the project

To run the project you will need a Twilio account and a Twilio phone number that can send SMS messages. Gather your Twilio Account Sid and Auth Token from the [Twilio console](https://www.twilio.com/console) and the phone number.

Then, clone the project, change into the directory and install the dependencies.

```bash
git clone https://github.com/philnash/send-sms-react-twilio.git
cd send-sms-react-twilio
npm install
```

Copy the `.env.example` file to `.env` and fill in your Twilio credentials and phone number.

Start the application on its own with the command:

```bash
npm run dev
```

Open the app at [localhost:3000](http://localhost:3000). You can now use the form to send SMS messages via your Twilio number.
