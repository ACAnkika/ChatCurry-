# ChatCurry-
A Chatbot-Based Smart Restaurant Assistant
ChatCurry is an intelligent restaurant assistant that lets users interact naturally to explore menus, ask questions, and place orders—all through a friendly chatbot interface. Designed to mimic the hospitality of a real waiter, ChatCurry offers a modern twist to the traditional dining experience.

## 🚀 Features

- 🧠 Chatbot-powered food ordering system
- 📋 Menu browsing a and item selection
- 🗃️ MySQL database to manage restaurant menu and orders
- 🔌 Python backend (Flask-style setup)
- 🌐 Clean HTML/CSS frontend with menu illustrations
- 💬 Dialogflow NLP integration (sample phrases included)

---

## 🗂️ Folder Structure

- ChatCurry/
│
├── backend/
│ ├── main.py # Core chatbot logic
│ ├── db_helper.py # Database interaction layer
│ ├── generic_helper.py # Utility functions
│ └── requirements.txt # Python dependencies
│
├── db/
│ └── pandeyji_eatery.sql # Sample database schema
│
├── dialogflow_assets/
│ └── training_phrases.txt # Sample training data for chatbot
│
├── frontend/
│ ├── home.html # User interface (static)
│ ├── styles.css # Frontend styles
│ ├── banner.jpg # Homepage banner
│ └── menu*.jpg # Menu images
│
└── README.md # Project overview and setup guide

yaml
Copy
Edit

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/ChatCurry.git
cd ChatCurry/backend
2. Install Python dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Set up MySQL database
Import the provided SQL file:

bash
Copy
Edit
mysql -u root -p < ../db/pandeyji_eatery.sql
You can modify the SQL script to fit your own restaurant's menu and structure.

4. Run the backend chatbot server
bash
Copy
Edit
python main.py
5. Access the frontend
Open the file frontend/home.html in your browser.

How ChatCurry Works
ChatCurry uses Dialogflow-style phrase matching to interpret user inputs such as:

“What’s on the menu?”

“I’d like to order 2 paneer rolls.”

“Add a mango lassi.”

It then responds intelligently and records the selections using Python + MySQL logic from the backend.


