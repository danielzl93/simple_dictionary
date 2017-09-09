# simple_dictionary

a simple multithreaded client-server dictionary

This is just a simple academic project that I have built to demonstrate how socket and multithread are implemented in Java. 
It only has three basic functionalities: search, add and remove words from a vocabulary file which can be .xml or .json. 
It also has basic GUI for both the client and server end user. As the project required, it has to be run through cmd with arguments. 

To run the dictionary, first try to launch the server though the following cmd:
java -jar Server.jar -p (enter any port number you want) -f Dictionary.xml (or you can build other files)

then try to launch to client though the following:
java -jar Client.jar -h (your hostname) -p (the port number that matches the server's port)
