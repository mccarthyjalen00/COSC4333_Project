# COSC4333_Project
--------------------------------------------------------------------------------------------
Students are required to implement a multi-threaded chat room service. The system will have one (multi-threaded) chat server, several chat rooms, and multiple chat clients. Socket interface is used to implement network communications.

Instructions
--------------------------------------------------------------------------------------------
Download the respected source code of the client-side (ChatroomClient.c) and server-side (ChatroomServer.c)

Before running these files on a Linux/Unix platform (ex: Ubuntu), make sure you install the 'gcc' command by doing the following:

sudo apt install gcc

Now, to compile these two programs, for the server-side, do the following command:

gcc ChatroomServer.c -o server -pthread

To compile the client-side, do the following command:

gcc ChatroomClient.c -o client

![Compile server   client](https://github.com/mccarthyjalen00/COSC4333_Project/assets/104598568/0e41136f-05f1-4971-863b-bcda9b3128f2)

Once these files compile successfully, they will produce a Unix Executable File.

![Unix Executable Files created](https://github.com/mccarthyjalen00/COSC4333_Project/assets/104598568/912b675f-9949-4be3-a126-ac7022dff4e5)

To start server and client(s), do the following commands:
For example, for the server do: ./server 1234
For the client side, do: ./client 1234

By doing the above command, the server will start, and the client(s) will be able to join that particular server.

![clients connecting to server](https://github.com/mccarthyjalen00/COSC4333_Project/assets/104598568/97f11897-8c07-4d49-a6f8-d04096a6babc)

Also, you can create more than one room as shown below. Just use a different port number to create another chatroom for client(s) to join.

![Chatroom 2](https://github.com/mccarthyjalen00/COSC4333_Project/assets/104598568/7dd02cba-0efe-4ba6-a962-549f4f1f962b)

Finally, to exit the chatroom, the client(s) just need to simply type 'exit', and they will automatically be disconnected from the chatroom. In addition, the server will display the client left.

![clients connecting to server](https://github.com/mccarthyjalen00/COSC4333_Project/assets/104598568/9e6bc80b-fe74-45f0-afce-5ba0e4ee70d8)







