This cerst are only for localhost

Generate comment: 
`openssl req -x509 -nodes -days 1024 -newkey rsa:2048 -keyout localhost.key -out localhost.crt -config ssl.conf -extensions 'v3_req'`