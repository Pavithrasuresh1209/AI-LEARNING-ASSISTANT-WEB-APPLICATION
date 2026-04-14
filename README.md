AI Learning Assistant                                                                
Live Demo:https://working-ai-learning-assistant-kkj9djfx4.vercel.app/


 
A personalized AI-powered learning assistant that converts notes, YouTube lectures, and audio classes into interactive study materials such as summaries, quizzes, flashcards, chat support, and performance analytics.

Overview

Students often prepare for exams using scattered resources like PDFs, screenshots, YouTube videos, and handwritten notes. This makes it difficult to track progress or understand learning gaps.

Working AI Learning Assistant provides a single platform where students can organize study material, generate learning resources using AI, and monitor their performance.

With this application, users can:
- Manage notes, lectures, and study content
- Generate quizzes and flashcards automatically
- Interact with AI based on their own content
- Track learning progress through a structured dashboard

The project is built using the MERN stack and integrates AI features to support active learning.

## Core Concept

The system follows a simple learning cycle:

Input:
Students provide notes, text, YouTube links, or audio lectures

AI Processing:
- Convert content into transcripts when required
- Generate summaries and key points
- Create quizzes and flashcards
- Enable chat interaction based on the content

Output:
- Students attempt quizzes and receive feedback
- Review flashcards to reinforce memory
- Analyze performance through a dashboard
- Get suggestions for improvement

## Features

### Dashboard and Analytics

The dashboard provides a clear overview of learning activity.

It includes:
- Total number of documents, lectures, quizzes, and flashcards
- Recent activity tracking
- Performance graphs showing progress over time
- Topic-wise understanding
- Pass and fail distribution
- AI-generated suggestions for next steps

### Documents Module

Users can create study documents from notes or typed content.

The AI can generate:
- Summaries
- Key points
- Quizzes
- Flashcards
- Chat-based assistance

This transforms static notes into interactive study material.

### Lectures Module

Supports both YouTube and audio-based learning.

YouTube Lectures:
- Users provide a video link
- The system extracts transcript
- AI generates study material from the transcript

Audio Lectures:
- Users upload audio files
- Audio is converted into text
- AI processes the content similarly

In both cases, users receive summaries, quizzes, flashcards, and chat support.

### Quizzes

Quizzes can be generated automatically or created manually.

After submission, users can see:
- Score and percentage
- Correct and incorrect answers
- Pass or fail status
- Detailed answer review

Users can also download results as PDF or CSV files.

### Flashcards

Flashcards can be generated or created manually.

Users can:
- Review cards regularly
- Mark them as known or unknown
- Improve retention through active recall

Flashcard data contributes to overall learning analytics.

### Learning Analytics and AI Guidance

The system tracks:
- Daily performance trends
- Topic-wise strengths and weaknesses
- Quiz performance history

AI provides suggestions such as:
- Topics to revise
- Recommended quizzes to retake
- Focus areas for improvement

## Technology Stack

Frontend:
- React with Vite
- Tailwind CSS
- React Router

Backend:
- Node.js
- Express.js
- MongoDB with Mongoose

AI Integration:
- Gemini API

Other Tools:
- JWT authentication
- Axios or Fetch for API communication
- PDF and CSV export functionality

## Project Structure

Working_AI_LEARNING_ASSISTANT/

backend/
- src/
  - routes/
  - controllers/
  - models/
  - utils/
- .env
- package.json

frontend/
- ai-learning-assistant/
  - src/
    - components/
    - pages/
    - services/
    - hooks/
  - .env.local
  - package.json
## Screenshots

### Dashboard
<img width="1841" height="904" alt="image" src="https://github.com/user-attachments/assets/52295019-4c0f-49d5-934c-9e1fdc3a26f6" />

### Documents
<img width="1871" height="909" alt="image" src="https://github.com/user-attachments/assets/943ee593-e80a-4e7a-9ed1-2e5fa2031383" />


### Lectures
<img width="1862" height="896" alt="image" src="https://github.com/user-attachments/assets/784db10f-d048-4a11-be45-56a35a6424ff" />


### Quiz Result

<img width="1900" height="891" alt="image" src="https://github.com/user-attachments/assets/04486ef7-b164-4b78-85e4-a6b518d255d6" />

### Flashcards
<img width="1893" height="884" alt="image" src="https://github.com/user-attachments/assets/f550e405-0f38-4dfa-ae5f-e16e9b544118" />

## Setup and Installation

Node version used:
v23.10.0

### Clone Repository

git clone https://github.com/Pavithrasuresh1209/Working_AI_LEARNING_ASSISTANT.git  
cd Working_AI_LEARNING_ASSISTANT

### Backend Setup

cd backend  
npm install  

Create a .env file inside backend folder:

MONGODB_URI=your_mongodb_connection_string  
JWT_SECRET=your_jwt_secret  
GEMINI_API_KEY=your_gemini_api_key  
PORT=5000  

Start backend:

npm run dev  

### Frontend Setup

cd frontend/ai-learning-assistant  
npm install  

Create .env.local file:

VITE_API_BASE_URL=http://localhost:5000  

Start frontend:

npm run dev  

## Project Importance

This project reflects a real-world learning solution rather than just a demo.

It demonstrates:
- Full-stack development using MERN
- Integration of AI into practical applications
- Clean architecture with separation of concerns
- Real-world features like analytics, downloads, and user interaction

It is suitable for academic submission as well as portfolio presentation.

## Future Improvements

- Teacher dashboard for monitoring students
- Spaced repetition for flashcards
- Role-based access control
- Cloud deployment for scalability


## Author

Pavithra Suresh  
 AI Learning Assistant Project
