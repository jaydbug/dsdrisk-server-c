# cs-423-dsdrisk
Server-side Game Manager for DSDRisk 2017.

               CS 423 Server Game Manager

What is it?
-----------
This is a very simple server using Java sockets. It can handle 
multiple client connections, log connections, and consume and 
broadcast messages.
Current version: 2.0

How to use:
-----------
How to start up the server and connect as a client

Uses:
- Client.java
- Server.java

*Starting Up The Server*
1) Open up a Terminal (or Command Prompt) window and cd into the main directory in our repo
2) Compile Server.java with `javac Server.java`
3) It should compile with no print statements
4) Start up the server with `java Server`

*Connecting as the Client*
1) Now that the server is running, you need to open a new terminal/cmd window
2) cd to the cs-423-dsdrisk directory again
3) Compile Client.java with `javac Client.java`
3) It should compile with no print statements
4) Run with `java Client`
5) It will prompt you for an IP Address. Leave it blank and press enter to connect locally.
6) This should prompt you with a client window that says, "Hello, you are client #..."
7) Verify that the window running the server has printed out "New connection with client#..."
8) In the client window, you can ping the server with a string and it will be returned in all uppercase
9) Send "." to end your session with the server

Version History:
----------------
version 1.0: attempt using Spark framework

version 2.0: completed server without using Spark. 

