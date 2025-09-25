# Collaborative Code Editor

A real-time collaborative code editor with integrated chat, video chat, code review, version control, and file management features. This project enables multiple users to work together seamlessly on code in shared rooms with rich collaboration tools.

---

## Features

- **Real-time Collaborative Editing:** Multiple users can edit code simultaneously in shared rooms.
- **Chat System:** Integrated chat for communication between room participants.
- **Video Chat:** WebRTC-based video chat to enable face-to-face collaboration.
- **Code Review:** Inline commenting on specific lines of code for peer review.
- **Version Control:** Undo/redo functionality, commit creation, and branch management within rooms.
- **File Management:** Create, delete, and synchronize multiple files within a room.
- **User Management:** Usernames and presence tracking in rooms.
- **Notification System:** Real-time notifications for user actions and system events.
- **Permission Management:** Control user permissions within rooms.
- **Merge Conflict Resolver:** Tools to handle merge conflicts during collaboration.
- **History Diff Viewer:** View changes and history of code edits.
- **Theme and Language Selection:** Customize editor theme and programming language.

---

## Tech Stack

### Frontend

- React 19
- Tailwind CSS for styling
- Monaco Editor for code editing
- Socket.io-client for real-time communication
- Simple-peer for WebRTC video chat
- React Router for navigation
- React Icons for UI icons

### Backend

- Node.js with Express framework
- Socket.io for real-time communication
- MongoDB with Mongoose for data persistence
- Redis for caching and session management
- JWT for authentication
- Bcryptjs for password hashing
- UUID for unique room IDs

---

## Installation

### Prerequisites

- Node.js (v16 or higher recommended)
- npm or yarn
- MongoDB instance
- Redis server

### Backend Setup

1. Navigate to the backend directory:

   ```bash
   cd backend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the `backend` directory and configure environment variables (e.g., MongoDB URI, Redis URL, JWT secret).

4. Start the backend server:

   ```bash
   npm run dev
   ```

### Frontend Setup

1. Navigate to the frontend directory:

   ```bash
   cd frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the frontend development server:

   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Usage

- Create or join a room to start collaborating.
- Use the code editor to write and edit code in real-time.
- Chat with other participants using the chat panel.
- Start video chat to communicate face-to-face.
- Add inline comments for code review.
- Manage files within the room: create, delete, and switch between files.
- Use version control features to undo/redo changes, create commits, and manage branches.
- Customize your editor theme and language preferences.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a pull request describing your changes.

---

## License

This project is licensed under the MIT License.

---

## Acknowledgments

- [Create React App](https://create-react-app.dev/)
- [Socket.io](https://socket.io/)
- [Monaco Editor](https://microsoft.github.io/monaco-editor/)
- [Simple-peer](https://github.com/feross/simple-peer)
- [Tailwind CSS](https://tailwindcss.com/)
