# mental-health-awareness-site
## 🌍 Overview
 
The **Mental Health Awareness Website** is an interactive web platform designed to raise awareness, reduce stigma, and improve access to mental health information and support.  
 
While many online platforms focus on global or Western contexts, this project emphasizes **local relevance**, **cultural sensitivity**, and **accessibility** — ensuring users from diverse backgrounds can find meaningful help and trusted information.  
 
The platform provides **reliable educational content**, **self-assessment tools**, and **links to verified local resources**, helping users take the first step toward better mental health.
 
---
 
## 🎯 Project Objectives
 
- Promote **mental health awareness** and reduce stigma in communities.  
- Provide **accurate and culturally relevant** information on mental wellness.  
- Offer **interactive tools** for self-evaluation and engagement.  
- Connect users to **local mental health services** and crisis helplines.  
- Contribute to **SDG 3 – Good Health and Well-Being** through technology.
 
---
 
## 🧩 Key Features
 
✅ Informative articles and wellness tips  
✅ Self-assessment quiz for emotional well-being  
✅ Directory of local counseling centers and hotlines  
✅ Chat support or AI-based assistant for quick guidance  
✅ User authentication and feedback form  
✅ Responsive design with an easy-to-use interface  
 
---
 
## 🧰 Tech Stack
 
| Category | Technology |
|-----------|-------------|
| Frontend | React.js, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Authentication | JWT, bcrypt |
| API Communication | Axios |
| Deployment | Vercel / Render (optional) |
 
---
 
## 🏗️ Project Structure
 mental-health-awareness-site/
│
├── client/                  # React frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar.jsx
│   │   │   ├── Footer.jsx
│   │   │   ├── HeroSection.jsx
│   │   │   ├── ResourceCard.jsx
│   │   │   └── ChatWidget.jsx
│   │   ├── pages/
│   │   │   ├── Home.jsx
│ │ │ ├── About.jsx
│ │ │ ├── Assessment.jsx
│ │ │ ├── Resources.jsx
│ │ │ └── Contact.jsx
│ │ ├── App.jsx
│ │ ├── main.jsx
│ │ └── styles/global.css
│
├── server/ # Express backend
│ ├── config/db.js
│ ├── models/User.js
│ ├── routes/authRoutes.js
│ ├── routes/resourceRoutes.js
│ ├── controllers/
│ │ ├── authController.js
│ │ └── resourceController.js
│ ├── middleware/authMiddleware.js
│ ├── server.js
│ └── .env.example
│
├── .gitignore
├── README.md
├── package.json
└── LICENSE
---## ⚙️ Setup Instructions### 1️⃣ Clone the Repository ```bash git clone https://github.com/joyous47/mental-health-awareness-site.git cd mental-health-awareness-site 
2️⃣ Install Dependencies
cd client && npm installcd ../server && npm install
3️⃣ Configure Environment Variables
Create a .env file inside the /server folder and add:
MONGO_URI=your_mongodb_connection_stringJWT_SECRET=your_jwt_secretPORT=5000 
4️⃣ Run the Application
Start Backend
cd server
npm run dev
Start Frontend
cd client
npm run dev
Access the website at 👉 http://localhost:5173
📡 API Endpoints (Examples)
Method	Endpoint	Description
POST	/api/auth/register	Register new user
POST	/api/auth/login	User login
GET	/api/resources	Fetch list of local support resources
POST	/api/feedback	Submit feedback form
💡 Future Improvements
Add multilingual and cultural adaptation features
Integrate real-time chatbot using OpenAI or Dialogflow
Add community discussion forum
Develop mobile app version
🤝 Contributing
Contributions are welcome!
If you’d like to collaborate, please fork this repo and create a pull request.
Fork the project
Create your feature branch (git checkout -b feature/your-feature)
Commit your changes (git commit -m 'Add feature')
Push to your branch (git push origin feature/your-feature)
Open a Pull Request
📜 License
This project is licensed under the MIT License — see the LICENSE file for details.

👩🏽‍💻 Author
1.  Stephen Katana-Computer Science 
    Email;[stephenngonyokatana@gmail.com] 
    🌐 GitHub:https://github.com/Katanajr

2.  Joy Borongo
    Email: [jbarongo011@gmail.com]
    🌐 GitHub:https://github.com/joyous47

“Your mind matters. Awareness is the first step toward healing