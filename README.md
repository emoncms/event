event
=====

Setup actions to occur when a feed goes above, below or is equal a set value. Set another feed or send an email.

Prowl, NMA, Curl, Twitter and Email methods native to application.

Email currently is biased towards gmail SMTP server.

Requirements

Run the next command at your (linux) shell to ensure that PHP5 scripts can run:
`sudo apt-get install php5-mcrypt php5-curl`

NMA - Notify my android

NMA is a message API for sending the events to your android phone or tablet.
You need to register at: https://www.notifymyandroid.com/ and make an API key.
Second you have to enter the API key at the event settings (at emoncms).
Beware that you have a treshold of only 5 messages a day with a trial account!

Pushover 

Pushover is an API that makes it easy to send real-time notifications to your Android and iOS devices.   The app does cost a small amount, but allows you to receive 7500 notifications per month.  You will need to obtain a user key and an application/API token.  Register at https://pushover.net/
