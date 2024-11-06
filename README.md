# Task Management Web Application

A unique task management web application designed to boost productivity through an aggressive, motivational approach. This application appreciates timely task completion and delivers tough-love reminders when tasks are overdue. It leverages the Groq API to emulate David Goggins' motivational style, providing a powerful tool for those who seek accountability and a strong push to achieve their goals.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Advantages](#advantages)
- [Disadvantages](#disadvantages)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Motivational Feedback**: Delivers positive reinforcement for on-time task completion and aggressive reminders for overdue tasks.
- **Interactive AI Chat**: Users can engage with an AI chatbot for real-time, motivational guidance.
- **Visual Analytics**: The analytics tab provides pie charts to visualize task completion rates, helping users track their productivity.
- **Tough-Love Style**: Emulates David Goggins' motivational approach for a unique, intense user experience.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (using Streamlit)
- **API**: Groq API for generating response texts
- **Data Visualization**: Matplotlib / Plotly (for pie charts)
- **Database**: SQLite / other database of choice (optional)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hariThorve/TaskManagerAI.git
   cd TaskManagerAI

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   Activate the virtual environment:

3. Windows:
   ```bash
   .\venv\Scripts\activate
4. Mac/Linux:
   ```bash
   source venv/bin/activate
   
5. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

6. Configure the Groq API:
   Add your Groq API key in the .env file (you will need to create this file if it does not already exist).
   Run the application:
   ```bash
   streamlit run app.py

