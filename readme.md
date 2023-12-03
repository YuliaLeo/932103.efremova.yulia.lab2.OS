# Server-Client 'C-application' for Linux

This project is a basic server-client application that handles receiving connections 
and signals.

## To make it work

1. Compile .c files on Linux
#### gcc server.c -o server
2. Start both server and client
#### ./server
#### ./client
4. Client automatically sends a message and displays message about it
5. Server receives the message and also displays a message
6. To test SIGHUP handling run, this gives you identification number of your process
#### pidof server
7. Then run
#### kill -SIGHUP -your-process-number

