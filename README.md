# TruthNode

A modern web application built with React, TypeScript, and Express, featuring a decentralized approach to truth verification and content management.

## 🚀 Features

- Modern React-based frontend with TypeScript
- Express.js backend server
- Tailwind CSS for styling
- Type-safe database operations with Drizzle ORM
- Real-time WebSocket communication
- Authentication and session management
- Responsive and accessible UI components
- Dark mode support

## 🛠️ Tech Stack

- **Frontend:**
  - React 18
  - TypeScript
  - Vite
  - Tailwind CSS
  - Radix UI Components
  - React Query
  - React Hook Form

- **Backend:**
  - Node.js
  - Express.js
  - TypeScript
  - Drizzle ORM
  - WebSocket

- **Database:**
  - PostgreSQL (via Neon Serverless)

- **Authentication:**
  - Passport.js
  - Express Session

## 📦 Prerequisites

- Node.js (v18 or higher)
- npm (v9 or higher)
- PostgreSQL database

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd DecentralizedTruth
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   - Copy `.env.example` to `.env`
   - Fill in the required environment variables

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## 📁 Project Structure

```
DecentralizedTruth/
├── client/           # Frontend React application
├── server/           # Backend Express server
├── shared/           # Shared types and utilities
├── assets/           # Static assets
└── dist/            # Production build output
```

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run check` - Type check the project
- `npm run db:push` - Push database schema changes

## 🔒 Environment Variables

Required environment variables (see `.env.example`):
- `DATABASE_URL` - PostgreSQL connection string
- `SESSION_SECRET` - Session encryption secret
- `NODE_ENV` - Environment (development/production)

## 📚 Documentation

- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Express.js Documentation](https://expressjs.com/)
- [Drizzle ORM Documentation](https://orm.drizzle.team/)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Vite](https://vitejs.dev/) for the amazing build tool
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Radix UI](https://www.radix-ui.com/) for the accessible UI components
- [Drizzle ORM](https://orm.drizzle.team/) for the type-safe database operations
