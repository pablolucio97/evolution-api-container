# Introduction

This project is a template image for using Evolution API for handling chats using N8N and Whatsapp.

## How to use this project

1. Clone this repository.
2. Generate a 32 characters authentication key (Encryption key 256) using the [ACTE website](https://acte.ltd/utils/randomkeygen).
3. Paste the generated authentication key as the value for the AUTHENTICATION_API_KEY variable on .env file.
4. Run the command `docker-compose up` to start the application.
5. Access the application on http://localhost:8081/manager address.
6. Paste your authentication key when prompted.
7. Click on "New instance" to create a new instance, and provide your name, channel(choose baileys because it's free), and your phone number and lick on "Save".
8. After the instance was created, click on "Get QR Code", read it using your phone to sync your Whatsapp data. 

Obs: Change your database credentials. Credentials are consciously exposed on this example, but it's recommended using a personal credential for handling databases.