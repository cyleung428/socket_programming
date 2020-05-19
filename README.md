# socket_programming
Task 1: Socket initialization

Description: initialize and create the TCP socket 

 

Both computers can initiate the connection. Suppose that two computers A and B would like to communicate with each other. If computer A serves as the “server” to wait for computer B to initiate the connection, computer A needs to get the inputs about its IP address and port number to listen. Then computer A needs to conduct the following task

Task 2: Bind IP and port, listen and accept connections

Description:

Bind the input local IP and port number.
Mark this socket as accepting connections.
Accept a connection on the socket.
 

Computer B inputs Computer A’s IP address and port number that Computer A is waiting for connection. Then Computer B conducts the following task.

Task 3: Connect to the peer with the given IP address and port number

 

Task 4: Send and receive the text

Bonus

Description: each computer can send or receive the text to or from the other participant.

In the above implementation,  after Computer A sends a message, it will have to wait for the reply from Computer B before it can send another message again. You can try to revise the program so that both sides can send and receive message at the same time. Thus, Computer A can send multiple messages before it gets the reply from Computer B. This implementation will also enable more than two participants in a session.

Hint: it is suggested using multithreading or non-blocking socket i.e. select() in C/C++ to implement it.
