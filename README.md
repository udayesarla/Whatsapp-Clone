# Whatsapp-Clone
Project Overview

The WhatsApp Clone Project aims to replicate the core features of the popular messaging app WhatsApp using React, Node.js, and MongoDB. The project's primary goal is to demonstrate a scalable and efficient real-time messaging application.

Features

1. User Registration and Login: Users can register with their phone numbers and passwords. They can log in to their accounts using their credentials.
2. Real-time Messaging: Users can send and receive messages in real-time, with support for text, images, and files.
3. Group Chats: Users can create and join groups, allowing them to communicate with multiple people simultaneously.
4. Message Typing Indicators: Users can see when their contacts are typing messages.
5. Delivered and Read Receipts: Users can see when their messages have been delivered and read by their contacts.
6. User Profiles: Users can view and edit their profiles, including their names, phone numbers, and profile pictures.
7. Contact List: Users can view their contact list, which displays the names and phone numbers of their contacts.

Technical Requirements

1. Frontend: React will be used to build the user interface and handle client-side logic.
2. Backend: Node.js will be used to handle server-side logic, including authentication, messaging, and database interactions.
3. Database: MongoDB will be used to store user data, messages, and group chat information.
4. Real-time Communication: Socket.IO will be used to enable real-time communication between clients and the server.

System Architecture

1. Client: The client-side application will be built using React and will handle user interactions, rendering the user interface, and sending requests to the server.
2. Server: The server-side application will be built using Node.js and will handle requests from clients, authenticate users, and manage real-time communication.
3. Database: The database will be used to store user data, messages, and group chat information.

APIs and Endpoints

1. Authentication API:
    - /register: Register a new user
    - /login: Log in an existing user
2. Messaging API:
    - /send-message: Send a message to a contact or group
    - /get-messages: Retrieve messages for a contact or group
3. Group Chat API:
    - /create-group: Create a new group
    - /join-group: Join an existing group
    - /leave-group: Leave a group
4. User Profile API:
    - /get-profile: Retrieve a user's profile information
    - /update-profile: Update a user's profile information
