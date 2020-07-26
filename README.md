# Node Socket Chat App

A chat application built using Node.js with Express and Socket.IO as part of [The Complete Node.js Developer Course](https://www.udemy.com/course/the-complete-nodejs-developer-course-2/) available on Udemy.

This application allows one to create and chat to other users in chatrooms.

It can be viewed on Heroku [here]().

Setup
-----

Ensure that you have Node.js already installed onto your system prior to anything else.

Download the repository contents and add them to the location of your choosing.

Once situated, navigate to the directory using the command line and use:

```bash
npm install
```

Doing so will obtain the necessary dependencies for the application.

Using the following to run this application locally on port 3000:

```bash
npm run start
```

Usage
-----

This application is a simple chatroom application that can be used to chat with other users.

Accessing the application will present a start screen to type in your **username** and **room name**. Once provided, you'll connect to the appropriate room with your username and can chat with others in the room.

Usernames per room are unique, and if an overlap is detected, an alert will appropriately appear.

Modules Used
-----------------
- [Express](https://www.npmjs.com/package/express)
- [Socket.IO](https://www.npmjs.com/package/socket.io)
- [bad-words](https://www.npmjs.com/package/bad-words)

Additional Libraries Used
-----------------
- [Mustache.js](https://github.com/janl/mustache.js)
- [Moment.js](https://momentjs.com/)
- [Qs](https://github.com/ljharb/qs)