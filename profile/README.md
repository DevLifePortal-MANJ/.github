# 📦 DevLife Portal - დეველოპერის ცხოვრების სიმულატორი

**A fun, interactive web platform that combines 6 independent mini-projects into one entertaining experience for developers!**

![Developer Lifestyle](https://img.shields.io/badge/Lifestyle-Developer-6366f1?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Web-10b981?style=for-the-badge)
![Fun Factor](https://img.shields.io/badge/Fun%20Factor-Maximum-ef4444?style=for-the-badge)

## 🎯 Project Overview

DevLife Portal is an interactive web platform designed to entertain and relax developers with personalized content based on zodiac signs. The platform serves as a playground where developers can have fun, play games, and consume interesting content.

### 🌟 Main Goal
Create a simple, fun, and interactive platform for developers where they can enjoy entertainment, games, and interesting content.

## 🏗️ Architecture Overview

```
DevLife Portal
├── 🔐 Authentication System
├── 🏠 Main Dashboard
├── 🎰 Code Casino
├── 🔥 Code Roasting
├── 🏃 Bug Chase Game
├── 🔍 Code Personality Analyzer
├── 💑 Dev Dating Room
└── 🏃 Meeting Escape Generator
```

## 📋 Project Structure

This project is organized into multiple repositories:

```
YourOrganization/
├── devlife-backend/          # .NET Backend APIs
├── devlife-frontend/         # React/Angular Frontend
├── devlife-db-scripts/       # Database migrations
└── README.md                 # Main documentation
```

## 🚀 Features

### 🔐 Authentication System
- **Registration**: Username, name, surname, birth date, tech stack, experience level
- **Auto-calculation**: Zodiac sign determination
- **Simple Login**: Username-only authentication (session-based)

### 🏠 Main Dashboard
- Welcome message with personalized zodiac-based daily horoscope
- Coding-related tips and advice
- "Lucky technology of the day"
- Navigation to all 6 mini-projects

### 🎰 Project 1: Code Casino
Test your code knowledge by betting on which code snippet works correctly!

**Features:**
- 2 similar code snippets (1 working, 1 with bugs)
- Betting system with points
- Daily challenges and leaderboards
- Streak system with zodiac luck multipliers

### 🔥 Project 2: Code Roasting
Solve coding challenges and get hilarious AI feedback on your solutions!

**Features:**
- Integration with Codewars/LeetCode/Exercism APIs
- In-browser code editor with syntax highlighting
- AI-powered roasting: *"This code is so bad, the compiler got depression"*
- Praise for good code: *"Bravo! Even my grandmother could write this code, but it's still good"*

### 🏃 Project 3: Bug Chase Game
Endless runner game where you're a developer running from bugs and deadlines!

**Features:**
- Auto-running character with jump/duck controls
- Obstacles: Bugs, Deadlines, Meetings
- Power-ups: Coffee (speed boost), Weekend (invincibility)
- Real-time multiplayer with WebSocket
- Achievement system and character customization

### 🔍 Project 4: Code Personality Analyzer
Connect your GitHub and discover what your coding style says about your personality!

**Features:**
- GitHub OAuth integration and repository analysis
- Analysis of commit messages, code comments, naming conventions
- Personality results: *"You are a Chaotic Debugger"*
- Shareable personality cards
- Celebrity developer comparisons

### 💑 Project 5: Dev Dating Room
Tinder-like dating simulator for developers!

**Features:**
- Profile setup with tech stack compatibility
- Swipe mechanics on static developer profiles
- Auto-match system with AI-powered chat
- Personalized dialogues based on tech preferences

### 🏃 Project 6: Meeting Escape Generator
Creative excuse generator to escape boring meetings!

**Categories:**
- Daily standup escapes
- Sprint planning avoidance
- Client meeting dodging
- Team building evasion

**Example excuses:**
- Technical: *"The server caught fire"*
- Personal: *"A cat broke into production"*
- Creative: *"AI gained consciousness and needs help"*

## 🛠️ Tech Stack

### Backend
- **.NET 8/9** - All APIs
- **PostgreSQL** - Main database (users, scores, game data)
- **MongoDB** - Static content (profiles, code snippets)
- **Redis** - Caching and session management
- **SignalR** - WebSocket communication
- **Minimal APIs** - For simplicity

### Frontend
- **React/Angular** - Your choice
- **Tailwind CSS** - Styling
- **Axios** - HTTP requests
- **Socket.io-client** - WebSocket connections

### External APIs
- **GitHub API** - Code analysis
- **OpenAI API** - AI features (optional)
- **Codewars API** - Coding challenges
- **Judge0 API** - Code execution

## 🎨 Design Guidelines

### Theme
- **Dark mode by default**
- **Developer-friendly design**
- **Active use of emojis** 😄
- **Responsive design**

### Color Palette
- **Primary**: `#6366f1` (Indigo)
- **Success**: `#10b981` (Green)
- **Danger**: `#ef4444` (Red)
- **Background**: `#0f172a` (Dark)

### Animations
- Smooth transitions
- Loading skeletons
- Success/Error animations
- Particle effects for achievements

## 📅 Development Timeline (5-7 days)

### Day 1: Foundation
- Authentication system
- Main dashboard
- Database setup (PostgreSQL + MongoDB)
- Project 1: Code Casino

### Day 2: Core Features
- Project 2: Code Roasting
- Project 3: Bug Chase Game (basic version)

### Day 3: Integrations
- Project 4: GitHub Analyzer
- External API integrations

### Day 4: Interactive Features
- Project 5: Dev Dating Room
- Project 6: Meeting Escape
- WebSocket features

### Day 5: Polish & Organization
- UI improvements
- Bug fixes
- Testing
- GitHub Organization setup

**⚠️ Extra Time**: Additional weekend available for those who need it (total 7 days).

## 🔧 Environment Setup

### Backend (.env)
```env
DATABASE_URL=postgresql://user:pass@localhost/devlife
MONGODB_URL=mongodb://localhost:27017/devlife
REDIS_URL=redis://localhost:6379
GITHUB_CLIENT_ID=xxxxxx
GITHUB_CLIENT_SECRET=xxxxxx
OPENAI_API_KEY=xxxxxx (optional)
JWT_SECRET=xxxxxx
```

### Frontend (.env)
```env
REACT_APP_API_URL=http://localhost:5000
REACT_APP_WS_URL=ws://localhost:5000/hub
```

## 🚀 Getting Started

1. **Clone the repositories**
   ```bash
   git clone https://github.com/YourOrganization/devlife-backend.git
   git clone https://github.com/YourOrganization/devlife-frontend.git
   git clone https://github.com/YourOrganization/devlife-db-scripts.git
   ```

2. **Set up databases**
   ```bash
   # PostgreSQL, MongoDB, and Redis setup
   cd devlife-db-scripts
   # Run migration scripts
   ```

3. **Start backend**
   ```bash
   cd devlife-backend
   dotnet run
   ```

4. **Start frontend**
   ```bash
   cd devlife-frontend
   npm install
   npm start
   ```

## 📝 Success Tips

✅ **Keep It Simple** - Don't overcomplicate the architecture  
✅ **Use Minimal APIs** - Fast and simple implementation  
✅ **Static Data** - Real users not required  
✅ **Focus on Fun** - Entertainment > Perfection  
✅ **Start Small** - MVP first, features later  
✅ **Be Creative** - Add your unique touch  

## 🎯 Project Priorities

1. **Simplicity** > Complex architecture
2. **Creativity** > Standard approaches  
3. **Clean Code** > Over-engineering

## 📞 Support

This project is designed to demonstrate your skills. Focus on clean code, creativity, and user experience.

---

**Remember**: You can use any resources (AI, Stack Overflow, documentation) to complete the project. The main thing is enthusiasm!

**Good luck!** 🚀

---

*This project will influence future real assignments and determines each person's level, capabilities, and code quality.*
