﻿# Sending-Mail-With-Node-to-Multiple-Recipients

To setup this on your device clone the repo and open it on your code editor and open the terminal.
1.In the terminal first run npm i command to install the dependencies
2.Now you have to create your own app password to be able to send mails from your id
3.Go to your google account->security->setup 2 step verification if not done already->in the same tab for 2 step verification scroll down to the bottom ->app passwords ->create any app name-> it will generate a password
4. Copy the password in the password field in auth option 
5. Enter your email id in username and also in mailOptions 'from' 
6. specify the recipients email id in the to part
7. then run node mailer.js command in the terminal 
8. check mails in the recipients id specified
