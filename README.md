
# Pfit - Fitness Application

**Pfit** is a next-generation fitness application designed to provide a gamified and socially engaging fitness experience. Users can track their activities, compete with friends, earn rewards, and gain awareness about different sports.

## Features

- 🏆 **Compete with Friends**: Track progress and challenge friends to complete fitness tasks.
- 🧍‍♂️ **3D Character**: A dynamic avatar mirrors your movements and shows real-time feedback.
- 🎯 **Task-Based Rewards**: Complete tasks to earn points, rewards, and coupons.
- 🏏 **Sports Awareness**: Learn about new sports, rules, and career opportunities from beginner to pro level.
- 📍 **Event Suggestions**: Discover local fitness and sports events powered by external companies.
- 💬 **AI Chat Support**: Chat with the AI assistant for help, guidance, and tips.
- 🏥 **Hospital Features (if enabled)**: Patient booking, pharmacy billing, staff management, doctor consultation, and more.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Flask
- **Database**: MySQL / SQLite
- **3D & Animation**: Unity / Three.js (optional)
- **AI & NLP**: LangChain, OpenAI API
- **Deployment**: Localhost / Render / Heroku

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/pfit.git
cd pfit
```

### 2. Create Virtual Environment & Activate It
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
# Enter your api key from groq on line 85 of app.py
python app.py
```

### 5. Open in Browser
Visit: [http://localhost:8050](http://localhost:8050)

## Contribution

Feel free to fork the repo, open issues or submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
