# React-Blogify Frontend

React-Blogify Frontend is the client-side application for the React-Blogify platform, built with React, Vite, and Tailwind CSS. It provides a modern, responsive interface for users to interact with the blogging platform.

---

## Features

- User authentication (register, login, logout)
- Create, edit, delete, and view blogs
- Like and favorite blogs
- Search blogs by keyword
- Profile management and avatar upload
- Responsive design with Tailwind CSS
- Custom hooks and context providers for state management

---

## Tech Stack

- **React** (with hooks and context)
- **Vite** (for fast development)
- **Tailwind CSS** (for styling)
- **Axios/Fetch** (for API requests)

---

## Folder Structure

```
src/
  assets/         # Images, fonts, icons
  components/     # Reusable UI components
  context/        # React context providers
  hooks/          # Custom React hooks
  pages/          # Page components
  providers/      # Context providers
  reducer/        # Reducers for state management
  utils/          # Utility functions
  index.css       # Global styles
  main.jsx        # App entry point
  App.jsx         # Main app component
```

---

## Getting Started

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn

### Installation

1. **Install dependencies:**
   ```bash
   npm install
   ```
2. **Start the development server:**
   ```bash
   npm run dev
   ```
3. **Open in browser:**
   Visit [http://localhost:5173](http://localhost:5173)

---

## Environment Variables

No special environment variables are required for local development. For production, configure API endpoints as needed.

---

## API Integration

The frontend communicates with the backend API (see `/api` folder) for all data operations. Update the API base URL in `src/utils/customFetch.js` if needed.

---

## Deployment

- Ready for deployment on Vercel or any static hosting platform.
- Build for production with:
  ```bash
  npm run build
  ```

---

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes.
4. Push to your fork and submit a pull request.

---

## License

This project is licensed under the MIT License.

---

For any questions or issues, please open an issue in the repository.

