Working socket demo with error reporting as of VS2015 x64. Sharing this because when I was making samples there
were limited working samples for my needs, and it was a bit hard to find all of the error reporting code.
-Greg Gutmann

The terms client and sever are used loosly: the Server is the code that starts first and waits for a connection. 
For this code the sever is the main receiver and the client is the main sender.
The code connects exchanges parameters - starts the main data sending loop - after a given time the "ClientFile"
sets a flag for the connection to be closed. 
There are many print lines commented out, they can be uncommented to watch more of what is going on in the CMD.
