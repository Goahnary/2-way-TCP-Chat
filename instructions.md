# Documentation

I decided to use the python programming language to create my chat program.
In order to write this I looked up some example programs and modeled my programs from that.

### Problems

Stopping the program was a challenge. You must stop everything in the correct order.
 Otherwise threads will keep running and sockets will stay connected and never stop your program.
The halting of the program was honestly the most difficult part.


### Requirements

In order to run my scripts you must have:

- at least one server/computer with linux installed
- Python 2.7 installed

### Set up

The script is currently set up to work on a single computer but it is capable of running on two.
The program itself takes care of setup and there should be no need for the user to change anything in the code.

### Running the program

To run my scripts open a terminal window and run socket-server.py with the command:

   python chat.py

After you have done this, open a second terminal and start the client script with the command:

   python chat.py

Once you have done this the program should now be running properly.

### Using The Program

**To use my program you will first observe the instructions on the screen:**

	Enter IP to connect or type listen:


*~If you are running this on one computer you may type "listen" on the first terminal  and type "localhost" on the second one.~*

**After you have done this enter some text to send to the server:**
	
	Enter IP to connect or type listen: localhost
	hello

**This will show up on the other terminal as "Client: hello"**

	Enter IP to connect or type listen: listen
	Client: hello

**In order to exit the program simply type "quit" and press enter:**

Client:

	quit
	Closing socket...
	success!
	Halting Text_Input
	done.

Server:

	quit
	Disconnecting...
	success!
	Halting Text_Input
	done.


### THANKS!

Thank you for using my program. I hope you enjoyed it.

