# Python_chat_room

I've made it through the basics of working with sockets, and now we're ready to try
to actually build something with them, so, in this sockets with Python tutorial, we're
going to build a console-based chat app.
First, the server needs to accept new connections from clients. From here, we need
to come up with some way to identify our unique users. We could display users by IP
address, but most people tend to rather come up with some sort of username, so our
server will first allow clients to connect and choose a username. Beyond this, the
server will collect incoming messages and then distribute them to the rest of the
connected clients.


How to Run Code-
First make sure you have installed threading and ​ tkinter.
First run server script
     $ python3 server.py
And then client script
     $ python3 client.py
