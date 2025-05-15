




The Real-Time Collaborative Document Editor is a full-stack web application designed to provide users with a seamless, 
Google Docs–like experience where multiple people can edit a shared document at the same time. Built using the MERN stack 
— MongoDB, Express.js, React.js, and Node.js — this project leverages modern web technologies to handle real-time text 
collaboration with the help of Socket.IO and Quill.js.

The primary goal of this project is to offer a lightweight, functional, and responsive collaborative environment that allows
users to create, edit, and store documents in the cloud. The frontend is built with React.js and uses Quill.js, a powerful
rich-text editor, to allow for formatting features such as bold, italics, headers, bullet points, links, and more. The backend
uses Node.js and Express to manage document-related API routes and establish a WebSocket connection via Socket.IO for real-time
syncing between users.

One of the core features of this editor is live synchronization. When one user edits the document, the changes are instantly
reflected in other connected clients without needing a manual refresh. This is done using Socket.IO rooms and broadcasting 
events to ensure minimal latency and smooth collaboration. In the backend, each document is saved in MongoDB using Mongoose 
schemas, ensuring persistence and allowing users to revisit or resume their work anytime.

The application is designed with a modular architecture, with the client/ and server/ folders clearly separating frontend and
backend concerns. This makes the codebase easier to maintain, test, and scale. The app also features auto-saving, meaning that 
changes are periodically saved to MongoDB without requiring users to click a “save” button.

This project demonstrates real-world use cases of web sockets, database interactions, and component-based UI development.
It also lays the foundation for future enhancements such as user authentication, document sharing permissions, chat features, and version control.
