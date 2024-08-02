# Realtime 1v1 MCQ Battle Arena 🏆

> A thrilling multiplayer quiz game developed for the Algozenith Quarterly Hackathon [May '24 - Jun '24]

## 🚀 Features

- ⚡ Real-time multiplayer MCQ battles
- 🔐 Secure user authentication
- ✏️ Full CRUD for MCQs
- 🎮 Modular game engine
- 🏠 Dynamic game lobby system
- 📱 Responsive UI
- 🛡️ Robust data integrity

## 🛠️ Tech Stack

| Backend | Frontend | Real-time |
|---------|----------|-----------|
| Django  | React    | Pusher    |
| DRF     | CSS      | WebSockets|
| JWT     |          |           |
| SQLite  |          |           |

## 🏗️ Setup

### Prerequisites

- Python 3.x
- Node.js
- npm/yarn
- Pusher account

(Setup instructions omitted for brevity)

## 🎮 How to Play

1. Register at `http://127.0.0.1:8000/register`
2. Login at `http://127.0.0.1:8000/login`
3. Enter the game lobby
4. Start battling!

## 🔗 API Endpoints

### Authentication
- `POST /register` - Sign up
- `POST /login` - Sign in (JWT)

### MCQ Management
- `GET /mcqs` - List MCQs
- `POST /mcqs` - Create MCQ
- `GET /mcqs/<uuid:pk>` - Retrieve MCQ
- `PUT /mcqs/<uuid:pk>` - Update MCQ
- `DELETE /mcqs/<uuid:pk>` - Delete MCQ

### Bonus
- `GET /protected` - Access protected view

## 🤝 Contributing

Contributions welcome! Fork, improve, pull request.

## 🙏 Acknowledgements

- Algozenith
- Django community
- React ecosystem
- Pusher team

---