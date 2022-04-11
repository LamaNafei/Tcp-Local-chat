# Tcp-Local-chat
python Chat program: 
The server should allow for multiple simultaneous clients (Multithread).
Any client can get a list of all other connected clients from the server.
The server should provide both clients sending to individual other clients, and clients sending to all other online users -- simultaneously.
The server should support some other functionality like groups, where clients can join groups tracked by the server, and messages can be sent to all clients in the group. Other option to send files to other clients. Each client must have an ID; used for connecting with the server, in order the server can keep a list of all connected clients. The client should access all functionality that the server supports. Therefore it must be able to request a list of the IDs for all other connected clients, send messages to other individual users, and send broadcast messages to all users.
