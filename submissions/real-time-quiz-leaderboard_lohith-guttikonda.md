# Real-Time Quiz Leaderboard

## Attendee/Team Details

**Name:** G. Lohith Sai

**GitHub Username:** lohith-guttikonda

**LinkedIn Profile:** https://www.linkedin.com/in/lohith-sai-guthhikonda-8aa864373/

**GitHub Project Repository:** https://github.com/your-username/your-project-repository

---

## Problem Statement Selected

**Problem Statement 61 – Real-Time Quiz Leaderboard**

Build a real-time multiplayer quiz game (Kahoot-style) using Valkey for game state, player scores, leaderboards, and pub/sub for live question broadcasting.

---

## Project Description

Real-Time Quiz Leaderboard is a multiplayer quiz platform where users can join a quiz room, answer questions in real time, and compete with other players on a live leaderboard.

The platform is designed for students, teachers, event organizers, and online communities who want an interactive quiz experience. It solves the problem of delayed score updates in traditional quiz systems by providing instant score calculations and live leaderboard updates.

---

## Approach

The project was designed by analyzing how modern quiz platforms work and identifying the core user flow:

1. Host creates a quiz room.
2. Players join using a room code.
3. Questions are broadcast to all participants.
4. Players submit answers within a timer.
5. Scores are updated instantly.
6. Leaderboard rankings change in real time.

Valkey is used for storing quiz sessions, player scores, rankings, and active game states. Pub/Sub functionality enables real-time communication between hosts and players, ensuring a smooth and engaging quiz experience.

---

## Tech Stack and Tools Used

**Frontend:** React.js, HTML, CSS, Tailwind CSS

**Backend:** Node.js, Express.js

**Database:** Valkey

**AI Tools/API:** ChatGPT, DeepSeek

**Cloud/Deployment:** Vercel, Render

**Other Tools:** Git, GitHub, VS Code, Postman

---

## Key Features

* Real-time multiplayer quiz rooms
* Room code-based joining system
* Live question broadcasting
* Instant answer validation
* Real-time leaderboard updates
* Player score tracking
* Host dashboard
* Timer-based quiz rounds
* Mobile-responsive interface
* Quiz session management

---

## What is Working?

* User interface completed
* Quiz room creation system
* Player joining functionality
* Question display mechanism
* Score calculation logic
* Leaderboard user interface
* Backend API setup
* Valkey integration structure

---

## What is Still in Progress?

* Full Pub/Sub implementation
* Authentication and user accounts
* Advanced leaderboard optimization
* Multiplayer synchronization testing
* Deployment and production testing
* Performance enhancements

---

## Screenshots or Demo

**Deployed Link:** Coming Soon

**Demo Video Link:** Coming Soon

**Screenshots:** To be added

---

## Challenges Faced

* Understanding Valkey data structures
* Managing real-time communication
* Synchronizing leaderboard updates
* Handling multiple players simultaneously
* Optimizing performance for live quizzes

---

## Learnings

* Real-time application development
* Valkey data management
* Pub/Sub architecture concepts
* Backend API development with Node.js
* State synchronization techniques
* Multiplayer application design

---

## Future Improvements

* AI-generated quiz questions
* Team-based competitions
* Voice-enabled quiz mode
* Detailed analytics dashboard
* Global leaderboards
* User profiles and achievements
* Multi-language support

---

## Final Note

This project demonstrates the power of Valkey in building fast and scalable real-time applications. The goal is to create an engaging and competitive learning platform where users can participate in quizzes, track their performance, and enjoy instant leaderboard updates.
