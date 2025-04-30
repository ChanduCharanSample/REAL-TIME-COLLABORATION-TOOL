# REAL-TIME-COLLABORATION-TOOL

COMPANY NAME : CODETECH IT SOLUTIONS

NAME : POTHINA CHANDRIKARANI

INTERN ID : CT6WVMW

DOMAIN NAME : MERN STACK 

DURATION : 6WEEKS

MENTOR : NEELA SANTOSH

DESCRIPTION
Overview
The Real-Time Collaboration Tool is a simple, web-based shared editor that allows multiple users to collaboratively edit text documents in real time. Built using Node.js, Express, and WebSockets, the application synchronizes changes instantly across all connected clients without the need for refreshing the page. It's ideal for collaborative note-taking, brainstorming, or live document editing scenarios.

Key Features
Real-Time Document Editing
Users can collaboratively edit the same text document simultaneously.

Any change made by one user is immediately reflected for all others.

Instant Synchronization
The app uses WebSockets to maintain a persistent, bidirectional connection between client and server.

Changes are propagated instantly to all connected users with minimal latency.

Multi-User Support
Multiple users can join the same session in different tabs or browsers.

Every user's edits are visible in real time, demonstrating seamless collaboration.

Cursor Position Tracking
Basic cursor tracking is included to demonstrate where other users are editing.

This can be extended to show user highlights, names, or color-coded cursors.

Simple, Clean Interface
The frontend provides a clean textarea-based editor built with plain HTML and JavaScript.

It can be enhanced or integrated with rich text editors for advanced features.

Tech Stack
Backend:
Node.js – JavaScript runtime for server-side development.

Express – Lightweight framework to serve static files and manage HTTP requests.

ws (WebSocket) – Enables real-time communication between server and connected clients.

Frontend:
HTML & JavaScript – Provides the base UI for document editing.

WebSocket API – Enables real-time syncing of content and cursor movements.

How It Works
Real-Time Syncing

As users type, their input is sent via WebSocket to the server.

The server broadcasts these changes to all other connected users instantly.

Cursor Tracking

Basic tracking of the cursor position is shared so others can see editing activity.

This can be expanded into full collaborative presence indicators.

Persistent WebSocket Connection

A live WebSocket connection allows continuous syncing without the need for polling or page refreshes.

Potential Enhancements
Usernames to identify individual collaborators.

Real-time collaborative cursors with color or label.

Document version history and rollback.

Integration with rich text editors like Quill or TipTap.

Conclusion
The Real-Time Collaboration Tool demonstrates how live communication and editing can be achieved using WebSockets and basic web technologies. It offers a strong foundation for building collaborative applications like shared editors, whiteboards, or task boards.


OUTPUT:

![Image](https://github.com/user-attachments/assets/7d7649eb-a463-428a-aaff-03619d60882f)

![Image](https://github.com/user-attachments/assets/6719ded6-aec6-4439-84ef-593400a4be81)
