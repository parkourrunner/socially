# Socially

Welcome to **Socially**, a modern and feature-rich social media application built with [Next.js](https://nextjs.org). Socially is designed to provide a seamless and interactive user experience, enabling users to connect, share, and engage in a clean and responsive interface.

**Live Demo**: [https://apk-socially.vercel.app/](https://apk-socially.vercel.app/)

---

## ✨ Features

- **User Authentication**: Secure and seamless login and registration powered by [Clerk](https://clerk.dev).
- **Post Creation**: Share your thoughts with text and images.
- **Likes and Comments**: Engage with posts by liking and commenting.
- **Real-Time Updates**: Dynamic updates for posts, likes, and comments.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Dark Mode**: Built-in theme switching with light and dark modes.

---

## 🛠️ Technologies Used

- **Frontend**: [Next.js](https://nextjs.org), [React](https://reactjs.org), [Tailwind CSS](https://tailwindcss.com)
- **Backend**: [Prisma](https://www.prisma.io) ORM with PostgreSQL
- **Authentication**: [Clerk](https://clerk.dev)
- **State Management**: React hooks and context
- **UI Components**: Radix UI and custom components
- **Notifications**: Real-time toast notifications with [react-hot-toast](https://react-hot-toast.com)

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally:

### Prerequisites

- Node.js 18 or higher
- PostgreSQL database
- Environment variables configured in a `.env` file (see `.env.example` for reference)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/socially.git
   cd socially
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up the database:
   ```bash
   npx prisma migrate dev
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📂 Project Structure

- **`src/actions`**: Server-side actions for handling posts, likes, and comments.
- **`src/components`**: Reusable UI components like `PostCard`, `CreatePost`, and more.
- **`src/generated`**: Auto-generated Prisma client and schema files.
- **`src/app`**: Application entry point and global styles.

---

## 📚 Learn More

To learn more about the tools and frameworks used in this project, check out the following resources:

- [Next.js Documentation](https://nextjs.org/docs)
- [Prisma Documentation](https://www.prisma.io/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

---

## 🌍 Deploy on Vercel

The easiest way to deploy Socially is to use the [Vercel Platform](https://vercel.com). Follow the [Next.js deployment guide](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to Socially, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add a meaningful commit message"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## 📝 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Created with ❤️ by Ali Salehi.
