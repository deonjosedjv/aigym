🏋️‍♂️ AI Real-time GYM Trainer

An interactive AI-powered fitness assistant built using Streamlit that helps users track and perform workouts in real-time.

🚀 Features
🔐 Simple login system using session state
🧠 AI-based workout guidance
🏋️ Exercise selection from predefined plans
📊 Real-time session tracking
🎯 Clean and interactive UI with Streamlit
⚡ Lightweight and fast
🛠️ Tech Stack
Frontend/UI: Streamlit
Backend: Python
State Management: Streamlit Session State
Environment: UV / Virtual Environment
📂 Project Structure
aigym/
│
├── main.py
├── services/
│   ├── auth/
│   │   └── login_wall.py
│   ├── state/
│   │   └── session_defaults.py
│   └── config/
│       └── workout_config.py
│
├── .venv/
└── README.md
⚙️ Installation
1. Clone the repository
git clone https://github.com/your-username/aigym.git
cd aigym
2. Create virtual environment (recommended)
python -m venv .venv
.venv\Scripts\activate   # Windows
3. Install dependencies
pip install streamlit
4. Run the app
uv run streamlit run main.py

or

streamlit run main.py
🧑‍💻 Usage
Open the app in browser
Enter your username
Select workout from sidebar
Start training session
🧠 How it Works
Uses Streamlit session_state to manage login and workout state
Sidebar dynamically updates based on user session
Modular structure for scalability
🐞 Known Issues
Session resets on refresh (default Streamlit behavior)
No persistent database yet
🔮 Future Improvements
🔐 Proper authentication system
📈 Workout analytics dashboard
🤖 Pose detection using OpenCV / Mediapipe
☁️ Cloud deployment
🤝 Contributing

Feel free to fork the repo and submit pull requests!

📄 License

This project is open-source and available under the MIT License.

👨‍💻 Author

Deon Jose

⭐ If you like this project, give it a star!