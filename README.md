# AI Interview Mocker

## 📌 Overview

**AI Interview Mocker** is a modern web application that provides AI-powered mock interviews. Built with Next.js and leveraging Google's Generative AI, it helps users practice technical interviews with real-time feedback. The application features user authentication, interview recording, and AI-powered analysis of responses.

Developed by **Nikhil Kumar Singh** ([@niikkhillll](https://github.com/niikkhillll))

## 🚀 Features

- 🔐 **Secure Authentication** with Clerk
- 🎤 **Speech-to-Text** for natural response capture
- � **Video Recording** for interview practice
- � **AI-Powered Feedback** using Google's Generative AI
- 🎨 **Modern UI** with Tailwind CSS and Radix UI
- 🌓 **Dark/Light Mode** support
- 📊 **Real-time Analysis** of interview responses
- 💾 **Database Integration** with Drizzle ORM

## 🏗 Project Structure

```
/ai-interview-mocker
├── /app/               # Next.js 13+ app directory
│   ├── /api/           # API routes
│   ├── (auth)/         # Authentication pages
│   └── (dashboard)/    # Main application pages
├── /components/        # Reusable React components
│   ├── /ui/           # UI components (shadcn/ui)
│   └── ...            # Other components
├── /lib/              # Utility functions and configurations
├── /public/           # Static assets
├── /utils/            # Helper functions
├── package.json       # Project dependencies
└── README.md          # Project documentation
```

## 🛠️ Tech Stack

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS, shadcn/ui
- **AI**: Google Generative AI
- **Database**: PostgreSQL (Neon)
- **ORM**: Drizzle ORM
- **Authentication**: Clerk
- **Deployment**: Vercel

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn
- Google Cloud API Key (for Generative AI)
- Clerk Account (for authentication)
- Neon Database (or any PostgreSQL database)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/niikkhillll/ai-interview-mocker.git
   cd ai-interview-mocker
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn
   ```

3. Set up environment variables:
   ```env
   # Clerk
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/dashboard
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/dashboard

   # Database
   DATABASE_URL=your_database_url

   # Google AI
   GOOGLE_AI_API_KEY=your_google_ai_key
   ```

4. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🧪 Running Tests

```bash
npm test
# or
yarn test
```

## 🚀 Deployment

1. Push to GitHub
2. Connect your GitHub repository to Vercel
3. Set up environment variables in Vercel
4. Deploy!

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Nikhil Kumar Singh**  
- GitHub: [@niikkhillll](https://github.com/niikkhillll)
- Email: nikhil05raghuwanshi@gmail.com

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) for the amazing framework
- [shadcn/ui](https://ui.shadcn.com/) for beautiful components
- [Clerk](https://clerk.com/) for authentication
- [Google AI](https://ai.google.dev/) for the powerful AI capabilities
