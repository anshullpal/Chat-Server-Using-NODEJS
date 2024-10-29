# Chat-Server-Using-NODEJS
Simple MQTT Chat Client

This Node.js script implements a basic chat client using the MQTT protocol. It connects to a public MQTT broker (test.mosquitto.org) and allows users to interact in a chat room named chat.

Requirements:

Node.js and npm (or yarn) installed on your system.
Setup:

Installation:
Open a terminal and navigate to your project directory. Run the following command to install the required dependency

npm install mqtt

npm install fs

npm install rl

Run the script using Node.js:
In first terminal:-
node client1.js

In Second terminal:- 
node client2.js

In third terminal:- 
node server.js

Enter Your Name:
You'll be prompted to enter your name. This name will be included in your chat messages.

Chat Interaction:
Type your chat messages into the console and press Enter to send them. You'll see messages from other users in the chat room as well.

Functionality:

Connects to the specified MQTT broker.
Subscribes to the chat topic to receive chat messages from other users.
Interactively retrieves your username from the console.
Publishes your chat messages to the chat topic, prepended with your username.
Logs received chat messages to the console.
