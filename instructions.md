# Documentation

I decided to use the python programming language to create my chat program.
In order to write this I looked up some example programs and modeled my programs from that.

### Problems

Sometimes stopping the program gets messy because of the threads but if one user is terminated with the "quit" command then the other will exit automatcally.

The biggest issue with my program is the formatting of the usernames. It works correctly at first but when a message is received the username of the sender is printed on the screen and the receivers username is removed and reprinted on the line below. This looks fine but unforunately beacause of the nature of the raw_input command I was unable to move the input to the end of the line. Fortunately, this is the only big issue in my program.

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

\* If python 3 is your default python version you may have to run the program with:

   python2.7 chat.py

### Using The Program

**To use my program you will first observe the instructions on the screen:**

	Welcome to my two way chatter box!
	Please type a username:

**After you have typed a username enter an IP or type listen:**

	Enter IP to connect or type listen:


*If you are running this on one computer you may type "listen" on the first terminal  and type "localhost" on the second one.*
*The listening server must be running before you type the ip address*

**After you have done this enter some text to send to the server:**
	
	Enter IP to connect or type listen: localhost
	[username]: hello

**This will show up on the other terminal as "Client: hello"**

	Enter IP to connect or type listen: listen
	Waiting for response...
	[sender's username]: hello

**In order to exit the program simply type "quit" and press enter:**

Client:

	quit
	Closing socket...
	success!
	Halting Text_Input
	done.

Server:

	Neither Server nor Client is Alive.
	Exiting Chat

### THANKS!

Thank you for using my program. I hope you enjoyed it.

