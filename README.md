# English L&D Platform - Level Tracker Demo 🚀

This project is a functional prototype designed to demonstrate an optimized **User Experience (UX) for Learning & Development (L&D)** environments [cite: 2026-02-18]. It focuses on reducing learner friction while maintaining robust data persistence [cite: 2026-02-18].

## 🧠 UX Strategy for Learning
* **Non-Punitive Feedback**: Instead of standard "Pass/Fail" screens, the platform uses a "Learning Review" system with amber-colored cards to highlight areas for improvement without discouraging the student [cite: 2026-02-18].
* **Frictionless Access**: Implementation of an email-only login (Magic Entry) to allow immediate access to learning paths while maintaining cross-device progress synchronization [cite: 2026-02-18].
* **Keyboard Accessibility**: Full support for the `Enter` key throughout the login and testing flow to ensure a "flow state" during high-concentration tasks [cite: 2026-02-18].

## 🛠️ Technical Stack
* **Frontend**: Vanilla JavaScript with Plus Jakarta Sans typography for high readability [cite: 2026-02-18].
* **Backend-as-a-Service**: Integrated with **Supabase** for real-time history tracking and question bank management via RPCs [cite: 2026-02-13].
* **Deployment**: Hosted on Netlify with automated CI/CD via GitHub [cite: 2026-02-18].

## 📊 Business Logic
The platform tracks 5-question intervals to determine CEFR levels (A1 to C2). It features an adaptive logic where:
* **Score >= 3**: Level cleared, invites the user to the next challenge [cite: 2026-02-18].
* **Score < 3**: Identifies the current steady level and suggests a retake to reinforce knowledge [cite: 2026-02-18].

---
*Developed as a UX/L&D technical demonstration.*
