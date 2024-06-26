# Mail-Server-and-Client-system
Built a simple mail server and client to send and receive mails in accordance with specific functionalities from SMTP and POP3 protocols. SMTP protocol is used while sending mail from client, and POP3 protocol is used while receiving mail in client.

# Requirements
Create a file names user.txt the same folder as the codes and enter names of two users in it. Create two folders, with the same name as that of users, in the same folder as the codes, each with a file mymailbox.txt, used for receiving the mails sent. 
The user should enter the mail to be sent in exactly the following format:

From: <username>@<domain name>
To: <username>@<domain name>
Subject: <subject string, max 50 characters>
<Message body – one or more lines, terminated by a final line with only a fullstop
character>

Wherever a space character is shown, one or more spaces can be there. No single line in the message body should more than 80 characters and the maximum no. of lines in the message is 50. Also, the To line should not contain more than one email address.

# Usage
Run the two servers smtpmail.c and pop3mail.c, then run mailclient.c to send or receive mail.
