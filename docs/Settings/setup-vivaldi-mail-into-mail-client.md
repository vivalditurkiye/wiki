# How do I set up Vivaldi email account in a mail client?

In your desktop or mobile email client create a new IMAP, or POP3 mailbox account using the following settings:

To receive e-mails, choose one the servers, below (Incoming server):
1. POP3:	pop3.vivaldi.net,
    - Port: 110,
    - Authentication method: normal password,
    - Connection security: STARTTLS
2. IMAP:	imap.vivaldi.net,
    - Port: 143,
    - Authentication method: normal password,
    - Connection security: STARTTLS

...or, instead, one of the two, below:
1. POP3s:	pop3.vivaldi.net,
    - Port: 995, 
    - Authentication method: normal password,
    - Connection security: SSL/TLS
2. IMAPs:	imap.vivaldi.net,
    - Port: 993,
    - Authentication method: normal password,
    - Connection security: SSL/TLS

To send e-mails, set the server, below (Outgoing server):
1. SMTP:	smtp.vivaldi.net, 
    - Port: 587,
    - Authentication method: normal password,
    - Connection security: STARTTLS

https://help.vivaldi.com/article/vivaldi-net-and-its-webmail/
