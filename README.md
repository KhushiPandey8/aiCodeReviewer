# AI Code Reviewer

AI Code Reviewer is a web application that utilizes Google's Gemini Flash 2.0 API to analyze and review code snippets. Built with React.js for the frontend and Node.js for the backend, it provides an AI-driven code review experience.

## Features

- **AI-Powered Code Review**: Uses Google's Gemini Flash 2.0 API for code analysis.
- **Syntax Highlighting**: Enhanced code readability with Prism.js and React Simple Code Editor.
- **Markdown Support**: Displays AI feedback in markdown format.
- **Real-time Feedback**: Fast and interactive code review experience.
- **Modern UI**: Designed with TailwindCSS and Lucide React icons.
- **Deployed on Render**: Accessible online with backend and frontend hosted seamlessly.

## Tech Stack

### Frontend
- React.js
- Vite
- TailwindCSS
- Axios
- Prism.js
- React Markdown
- React Simple Code Editor

### Backend
- Node.js
- Express.js
- @google/generative-ai (Gemini Flash 2.0)
- Dotenv
- Cors

## Installation

### Prerequisites
Ensure you have **Node.js** and **npm** installed.

### Clone the Repository
```sh
git clone https://github.com/yourusername/aicoderreviewer.git
cd aicoderreviewer
```

### Backend Setup
```sh
cd backend
npm install
npm start
```

### Frontend Setup
```sh
cd ../frontend
npm install
npm run dev
```

## Deployment
This project is deployed on **Render**. You can access it [here](https://your-app-url.onrender.com).

### Deploying on Render
1. Create a **Render** account.
2. Deploy the **backend** as a web service.
3. Deploy the **frontend** as a static site and configure it to point to the backend URL.
4. Set up necessary **environment variables**.

## Contributing
We welcome contributions! Follow these steps to contribute:

### Fork the Repository
1. Go to the [repository](https://github.com/yourusername/aicoderreviewer) on GitHub.
2. Click on the **Fork** button (top right corner) to create a copy of the repository under your GitHub account.

### Clone Your Fork
```sh
git clone https://github.com/yourusername/aicoderreviewer.git
cd aicoderreviewer
```

### Create a Branch
```sh
git checkout -b feature-name
```

### Make Changes and Commit
1. Make your changes in the appropriate files.
2. Stage your changes: `git add .`
3. Commit your changes: `git commit -m "Added new feature"`

### Push to Your Fork
```sh
git push origin feature-name
```

### Create a Pull Request
1. Go to your forked repository on GitHub.
2. Click on the **Compare & pull request** button.
3. Add a descriptive title and comment about the changes.
4. Submit the **Pull Request**.

### Contribution Path
- **Frontend contributions**: `frontend/`
- **Backend contributions**: `backend/`
- **API integrations**: `backend/server.js`
- **UI/UX improvements**: `frontend/src/`

## License
This project is licensed under the **ISC License**.

## Author
Developed by **Khushi Pandey**.

---
Feel free to contribute and improve AI Code Reviewer! 🚀

