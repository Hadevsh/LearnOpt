# LearnOpt (in-dev)

**LearnOpt** is a smart, AI-assisted time planning web app that helps you achieve your learning goals by intelligently scheduling your study sessions. Whether you're preparing for exams or just trying to learn consistently, LearnOpt adapts to your routine and helps you optimize your study time.

## Features

- **Goal Setting**: Define weekly goals like "Study Math for 5 hours"
- **Availability Planner**: Set times when you're free or unavailable (e.g., school hours)
- **AI-Powered Scheduling**: Get personalized study time suggestions based on your past habits and availability
- **Progress Tracking**: Mark sessions as complete, give feedback, and let LearnOpt adapt
- **Dynamic Calendar**: Visualize your week using a built-in calendar interface

## Tech Stack

- **Backend**: Flask, SQLAlchemy, Python
- **Frontend**: Jinja2, Bootstrap, FullCalendar.js
- **Database**: SQLite (dev) / PostgreSQL (prod)
- **Machine Learning**: pandas, scikit-learn

## Project Structure

```
learnopt/
├── app/
│ ├── init.py
│ ├── routes.py
│ ├── models.py
│ ├── scheduler.py # AI/ML scheduling logic
│ ├── templates/
│ ├── static/
├── config.py
├── run.py
├── requirements.txt
├── README.md
```

## Setup Instructions

1. **Clone the Repository**
```
bash
git clone https://github.com/Hadevsh/LearnOpt
cd LearnOpt
```

2. **Create a Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install Dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the App**
```bash
flask run
```

5. **Access in Browser**
```
http://127.0.0.1:5000
```

---

## Screenshots (to be added)

- [ ] Dashboard
- [ ] Goal input
- [ ] Calendar view
- [ ] Feedback popup

## Future Plans

- Google Calendar sync
- Mobile-friendly UI / PWA support
- Natural language goal input
- Advanced ML models for personalized scheduling
- Group planning features

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.


## License

This project is licensed under the MIT License.
