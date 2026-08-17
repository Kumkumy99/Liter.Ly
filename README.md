# LITER.LY

### Read. Review. Discuss. Discover.

LITER.LY is a full-stack book community platform where readers can discover books, share reviews, discuss them through threaded conversations, join reading groups, and get personalized help from AI.

---

## 🚧 Project Status

LITER.LY is currently under active development.

The project is being built incrementally, with a focus on learning and implementing real-world full-stack development practices.

---

## ✨ Features

### 👤 Authentication & Users
- User signup and login
- JWT-based authentication
- User profiles
- Role-based authorization
- User review history
- Ban functionality for moderation

### 📚 Books
- Browse books
- Search by title or author
- Filter by genre
- Pagination
- Book details
- Add books

### ⭐ Reviews
- Rate books from 1–5 stars
- Write reviews
- Edit and delete own reviews
- One review per user per book
- Average book ratings

### 💬 Threaded Discussions
- Comment on reviews
- Reply to comments
- Unlimited comment nesting
- Recursive comment tree
- Edit and delete own comments
- Soft deletion

### 👥 Reading Groups
- Create reading groups
- Join and leave groups
- Group membership management
- Group admins
- Group discussion posts
- View group members

### 🛡️ Moderation
- Report reviews and comments
- Admin moderation dashboard
- Resolve or dismiss reports
- Hide reported content
- Ban users
- Soft deletion to preserve discussion structure

### 🤖 AI Features

#### Reading Companion
An AI-powered companion that helps users discuss books, understand passages, and explore themes.

#### Personalized Recommendations
Recommendations based on books users have rated or interacted with.

> Advanced RAG-based features are intentionally not part of the initial version.

---

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- Tailwind CSS
- TanStack Query
- Context API
- React Hook Form
- Zod

### Backend
- Python
- FastAPI
- Pydantic
- SQLAlchemy 2.0
- Alembic

### Database
- PostgreSQL

### Authentication
- JWT
- Password hashing

### Testing
- pytest
- HTTPX

### DevOps
- Docker
- Docker Compose
- GitHub Actions

### Deployment
- Frontend → Vercel
- Backend → Render / Railway
- Database → Neon / Supabase

---

 
