# News Aggregator

A **full‑stack News Aggregator** web application designed to collect and display top news headlines from multiple categories (National, International, Business, Sports, Technology) in one unified interface.  

The project uses a **Flask (Python)** backend for routing and data handling, and a **responsive frontend** built with HTML, CSS, and JavaScript to provide a clean and user‑friendly experience.

## Features
- **Category-based browsing**: National, International, Business, Sports, Technology.
- **Top 5 Headlines** per category for a quick, uncluttered view.
- **Refresh functionality**: Update news without restarting the server.
- **Responsive design**: Works well across devices.
- **Modular architecture**: Easy to extend with APIs (e.g., NewsAPI.org).


## Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Python (Flask)
- **Data**: Static/mock data (API-ready)
- **Optional API**: [NewsAPI.org](https://newsapi.org)
- **IDE**: Visual Studio Code


## Project Structure
News-Aggregator/
├── app.py # Main Flask application
├── templates/
│ └── index.html # Frontend HTML template
├── static/
│ └── css/
│ └── style.css # Styling for the app
├── screenshots/ # Screenshots of the project
└── README.md # Project documentation


## Setup & Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/News-Aggregator.git
   cd News-Aggregator
