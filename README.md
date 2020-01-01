# Connection could not be established with host relay-hosting.secureserver.net :stream_socket_client(): unable to connect to relay-hosting.secureserver.net:587 (Connection refused)

#If You see this Error (Godaddy server (windows Hosting)).


#Change .env File in Lavavel And Replace Code.

MAIL_DRIVER=smtp

MAIL_HOST=relay-hosting.secureserver.net

MAIL_PORT=25

MAIL_USERNAME=exmaple.mailgun.org[exmple@gmail.com]

MAIL_PASSWORD=[enter your password]

MAIL_ENCRYPTION=null

