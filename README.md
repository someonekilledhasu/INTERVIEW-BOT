# TrustInterview AI

AI-powered interview bot that reads your resume and asks personalised, bias-free questions.

## Features
- Resume upload (PDF)
- 7 AI-generated personalised questions
- Voice answers via microphone
- Live scoring 0-10 per answer
- Final report with hire/no-hire recommendation
- Bias-free questions (no age, gender, race questions)

## Tech Stack
- Frontend: React.js
- Backend: Node.js + Express
- AI: Google Gemini 1.5 Flash (Free)

## Setup
## Prerequisites

Before running the project, ensure you have:

- Node.js (v18 or later recommended)
- npm
- Google Gemini API Key

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/triveni030208-cpu/INTERVIEW-BOT.git
cd INTERVIEW-BOT
```

### 2. Backend

```bash
cd backend
npm install
```

Create your environment file using the provided example:

```bash
cp .env.example .env
```

Update the values in `.env` with your own credentials.

Start the backend server:

```bash
node server.js
```

### 3. Frontend Setup

Open a new terminal:

```bash
cd frontend
npm install
npm start
```

The application will be available at:

```text
http://localhost:3000
```

## Environment Variables

The project includes a `.env.example` file.

Create your local environment file:

```bash
cp .env.example .env
```

Then update the required values before starting the application.

## Project Structure

```text
INTERVIEW-BOT/
├── backend/
├── frontend/
└── README.md
```

## Contributing

Contributions are welcome. Feel free to submit issues and pull requests for improvements, bug fixes, and new features. 
To contribute:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your fork
5. Open a Pull Request
## Author
Triveni Reddy - github.com/triveni030208-cpu
