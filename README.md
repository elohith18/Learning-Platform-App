# AI Learning Platform

A full-stack learning platform that uses AI to help learners explore topics, get explanations, and make progress at their own pace.

## Features

- Explore learning content and topics
- Ask AI questions and get explanations
- Organize or save learning materials
- Track learning progress
- Create an account and sign in
- Responsive interface for desktop and mobile

> Keep only the features that are actually implemented in your app.

## Tech Stack

- **Frontend:** React, JavaScript, HTML, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **AI:** Claude
- **Other:** JWT, Cloudinary

## How It Works

1. A learner chooses a topic or enters a question.
2. The app sends the request to its backend.
3. The backend gets an AI response and returns it to the app.
4. The learner reviews the answer and continues learning.

Update these steps to match your app’s actual workflow.

## Run Locally

### Requirements

- Node.js and npm
- MongoDB, or a MongoDB Atlas connection
- An API key for your AI provider, if your app uses one

### 1. Clone the repository

```bash
git clone ADD_REPOSITORY_URL
cd ADD_PROJECT_FOLDER
```

### 2. Install dependencies

Use the commands that match your project structure. For example, if the frontend and backend have separate folders:

```bash
cd server
npm install

cd ../client
npm install
```

### 3. Configure environment variables

Create a `.env` file in the backend folder. Use the variable names your app expects. For example:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
AI_API_KEY=your_ai_provider_api_key
```

Never commit real passwords, API keys, tokens, or secret keys to GitHub.

### 4. Start the app

Run the scripts defined in each folder’s `package.json`. For example:

```bash
# In the server folder
npm run dev
```

```bash
# In the client folder
npm run dev
```

## Project Structure

Update this example to match your repository:

```text
ai-learning-platform/
├── client/          # React frontend
├── server/          # Node.js and Express backend
├── .gitignore
└── README.md
```

## What I Learned

- Building a full-stack application with the MERN stack
- Connecting a React frontend to a Node.js and Express API
- Integrating an AI service into a web application
- Storing and retrieving application data with MongoDB


