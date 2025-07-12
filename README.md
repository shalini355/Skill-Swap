# 🔄 Skill Swap Platform

A real-time web application that allows users to exchange skills with others based on mutual needs. Users can list skills they offer and request ones they want — building a trusted and collaborative learning ecosystem.


---

## 🚀 Features

### 👤 User Side:
- Register & login securely
- Create a profile with:
  - Name, location, availability
  - Skills Offered & Wanted
  - Profile photo (optional)
  - Public/private visibility
- Browse and search other profiles by skill
- Send, accept, reject or delete skill swap requests
- View current and pending requests
- Leave feedback after swaps

### 🛠️ Admin Panel:
- Approve/reject inappropriate skill descriptions
- Ban users violating platform rules
- View and monitor all swap activity
- Send platform-wide alerts (e.g., downtime notices)
- Download CSV reports of feedback, swaps, and user activity

---

## 🌈 Tech Stack

| Layer         | Tech Used                         |
|---------------|-----------------------------------|
| **Frontend**  | HTML, TailwindCSS, Vanilla JavaScript |
| **Backend**   | Node.js, Express.js               |
| **Database**  | MongoDB + Mongoose                |
| **Auth**      | JWT (JSON Web Tokens)             |
| **Styling**   | TailwindCSS with dark/light themes |
| **Version Control** | Git + GitHub               |

---

## 🎨 Theme

- **Background**: Dark Slate Gray (`#0F172A`)
- **Primary Color**: Emerald (`#10B981`)
- **Accent**: Amber (`#FBBF24`)
- **Typography**: Slate-100 to Slate-400
- **Dark Mode**: Built-in toggle available

---

## 🧩 Project Structure

SkillSwapPlatform/
├── public/
│ ├── index.html
│ ├── login.html
│ ├── register.html
│ └── js/
│ └── main.js
├── backend/
│ ├── server.js
│ ├── routes/
│ ├── models/
│ └── controllers/
├── .env
├── README.md
└── package.json

## ⚙️ How to Run Locally

```bash
# Clone repo
git clone https://github.com/yourusername/skill-swap-platform.git
cd skill-swap-platform

# Backend setup
cd backend
npm install
touch .env
# Add MongoDB connection URI and JWT_SECRET in .env

# Start backend
node server.js

# Open frontend in browser via VS Code Live Server or direct file open

🔮 Future Enhancements
Add chat or messaging system

Skill endorsements

Availability calendar view

AI-based skill matching suggestions

Upload skill proof (certificates/videos)

🏆 Built For
Odoo Hackathon 2025

"Build apps that solve real human problems."

🙌 Credits
UI/UX: TailwindCSS magic ✨
Powered by: Node.js + MongoDB
