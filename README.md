# cc_callbox
twilio door callbox app.

This app uses twilio to automatically 'buzz in' visitors when the intercom button is pressed.
An sms is then sent to staff to alert them that the door has been opened.

There is also a closed state that informs visitors that the business is currently closed. An sms is then sent to a manager to inform them that someone has attempted to access the premisis through the front door.

The third state forwards the call to a previously specified phone number.

The three states can be selected via the twilio contol panel.

Coming Soon:
Web interface to change between states without logging into twilio.

NB:
The phone numbers and business name in this version of the app have been altered for privacy reasons.
