# CLIENT SERVER-REMOTE SHELL Connection

> A Client Server to implement a simple remote shell connection where the server process and the client process will run on two different machines and communicate using Sockets.
 When the server gets a client, forks and, let the child process take care of the client in a separate function, while the parent process goes back to wait for the next client. In this way, the server is capable to service multiple clients at the same
time. Built using C, Unix

## Table of contents
* [Technologies](#technologies)
* [Running the Application](#running-the-application)
* [Contact](#contact)

## Technologies
* Technologies - C, Unix

## Running the Application
* Step 1: Initially, Login into Bitwise SSH Client with two/many Unix host names; one to make act one as server and others as clients and open the respective terminals.
* Step 2: First, run the server.c program in one terminal specifying the port number for clients to connect with the server.
* Step 3: Secondly, run the client.c programs in other terminals specifying the same port number given in server terminal and the clients will now be connected to server.
* Step 4: Now, the Clients can send any Unix Commands and get the output from server.

## Contact
[Sabiha Begum Jaggir Hussain](https://sabihabegumj.com/) - feel free to contact me!
