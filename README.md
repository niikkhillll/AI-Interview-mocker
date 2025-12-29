# AI Mock Interviewer - Backend & Frontend

## 📌 Overview

**AI Mock Interviewer** is a platform that provides mock interview questions and evaluates user responses using AI. The project includes both **backend (Node.js, Express, LangChain.js)** and **frontend (React.js)** components.

Developed by **Nikhil Kumar Singh** ([@niikkhillll](https://github.com/niikkhillll))

---

## 🚀 Features

- 🔐 **User Authentication**
- 📌 **Select Field & Experience Level**
- 🎤 **Record Audio & Video Responses**
- 🧠 **AI Feedback on Answers**
- 🎨 **Interactive User Interface**
- 📊 **Performance Analytics**
- 🔄 **Real-time Response Evaluation**

---

## 🏗 Project Structure

```
/AI-Interview-mocker
├── /backend/          # Node.js & Express server
├── /frontend/         # React.js application
└── README.md          # Project documentation
```

---

## �️ Setup & Installation

### Prerequisites
- Node.js (v14+)
- npm or yarn
- Google Gemini API Key

### Backend Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/niikkhillll/AI-Interview-mocker.git
   cd AI-Interview-mocker/backend
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Create a `.env` file in the backend directory and add your API key:
   ```env
   GEMINI_API_KEY=your_gemini_api_key
   PORT=5000
   ```

4. Start the development server:
   ```sh
   npm start
   ```
   The backend will be available at `http://localhost:5000`

### Frontend Setup

1. Navigate to the frontend directory:
   ```sh
   cd ../frontend
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm start
   ```
   The frontend will be available at `http://localhost:5173`

---

## 🚀 Deployment

### Vercel Deployment

1. Install Vercel CLI:
   ```sh
   npm install -g vercel
   ```

2. Deploy backend:
   ```sh
   cd backend
   vercel --prod
   ```

3. Deploy frontend:
   ```sh
   cd ../frontend
   vercel --prod
   ```

---

## 🛠️ Built With

- **Frontend**: React.js, TailwindCSS
- **Backend**: Node.js, Express
- **AI/ML**: Google Gemini API, LangChain.js
- **Authentication**: JWT
- **Database**: MongoDB
- **Deployment**: Vercel

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Nikhil Kumar Singh**  
- GitHub: [@niikkhillll](https://github.com/niikkhillll)
- Email: nikhil05raghuwanshi@gmail.com

---

## 🙏 Acknowledgments

- [LangChain.js](https://js.langchain.com/) for AI integration
- [Google Gemini](https://ai.google.dev/) for powerful AI capabilities
- All the open-source libraries used in this project

🚀 Happy Coding!
