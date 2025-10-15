# XLone

Xlone is a full-stack clone of the social media website X (formerly Twitter). It allows users to sign up, log in, create posts, follow/unfollow other users, update their profiles, and interact with a modern social feed.

## Technologies Used

### Frontend

- **React**: UI library for building interactive user interfaces.
- **React Router**: Handles client-side routing.
- **TanStack Query (React Query)**: Data fetching, caching, and state management for server state.
- **Tailwind CSS & DaisyUI**: Utility-first CSS framework and UI components for rapid styling.
- **Vite**: Fast development server and build tool.
- **React Hot Toast**: Toast notifications for user feedback.
- **React Icons**: Icon library for UI elements.

### Backend

- **Node.js & Express**: Server-side JavaScript runtime and web framework.
- **MongoDB & Mongoose**: NoSQL database and ODM for data modeling.
- **JWT (jsonwebtoken)**: Authentication using JSON Web Tokens.
- **bcryptjs**: Password hashing for secure authentication.
- **Cloudinary**: Image upload and management.
- **dotenv**: Environment variable management.
- **cookie-parser**: Parses cookies for authentication.
- **CORS**: Cross-Origin Resource Sharing middleware.

## Features

- User authentication (signup, login, logout)
- Profile management (edit profile, upload images)
- Create, view, and interact with posts
- Follow/unfollow users
- Suggested users
- Responsive UI

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/xlone.git
   cd xlone
   ```
2. **Install dependencies:**
   ```bash
   npm install
   cd frontend && npm install
   ```
3. **Set up environment variables:**
   - Create a `.env` file in the root and backend folders with required secrets (see code for details).
4. **Run the backend:**
   ```bash
   npm run dev
   ```
5. **Run the frontend:**
   ```bash
   cd frontend
   npm run dev
   ```
6. **Open in browser:**
   - Visit `http://localhost:3000` for the frontend.

## Folder Structure

```
xlone/
├── backend/
│   ├── controllers/
│   ├── db/
│   ├── lib/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   ├── index.html
│   └── package.json
├── package.json
└── README.md
```

## License

This project is licensed under the ISC License.

---

**Place the `README.md` in the root of your project.** This is the standard convention so that it is visible on GitHub and easily accessible to anyone viewing your repository.
