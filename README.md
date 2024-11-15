# RouteCraft

## Personalized Travel Itinerary Generator

Welcome to RouteCraft, your one-stop solution for planning the perfect trip! Whether you're looking for adventure, relaxation, or a mix of both, RouteCraft generates detailed, personalized itineraries based on your preferences, budget, and trip duration.

## Features

**User Authentication:** Secure login system for personalized experiences.

**Personalized Recommendations:** Tailored itineraries based on your interests, trip budget, and duration.

**Weather Integration:** Real-time weather updates for your destination to help you plan better.

**Real-Time Data:** Leveraging travel APIs for accommodation, activities, and travel route suggestions.

**User-Friendly Interface:** Intuitive design for seamless trip planning.

## Project Structure


RouteCraft/
│
├── app.py                 # Main Flask application

├── gen.py                 # Generative model for creating itineraries

├── templates/             # HTML templates for rendering pages

│   ├── index.html         # Landing page

│   ├── dashboard.html     # User dashboard with personalized itinerary

│   ├── login.html         # User login page

│   └── ...                # Other HTML pages

│
├── static/                # Static assets like CSS, JS, and images

│   ├── css/

│   ├── js/


│   └── images/
│
├── requirements.txt       # Python dependencies

├── README.md              # Project documentation

├── .gitignore             # Files and directories to ignore in Git

└── ...                    # Other supporting files

## Installation and Setup
### 1. Clone the Repository
bash
git clone https://github.com/RitikaMishra23/RouteCraft-Your-Personal-Itinerary-Generator.git

cd routecraft
### 2. Install Dependencies
Make sure you have Python 3.7 or higher installed. Then, install the required dependencies:

bash
pip install -r requirements.txt

### 3. Set Up API Keys
Obtain API keys for the weather and travel services (e.g., OpenWeather, Google Maps API).
Create a .env file in the root directory and add your keys:

WEATHER_API_KEY=your_weather_api_key

TRAVEL_API_KEY=your_travel_api_key

### 4. Run the Application
Start the Flask application:
bash
python app.py
The app will run at http://127.0.0.1:5000.

## Usage
**Sign Up/Login:** Create an account or log in to your existing account.

**Input Preferences:** Enter details like budget, trip duration, and interests.

**Get Your Itinerary:** View and download your personalized travel itinerary.

**Weather Insights:** Check real-time weather conditions for your travel destination.

## Technologies Used

**Backend:** Flask (Python)

**Frontend:** HTML, CSS, JavaScript

**APIs:** OpenWeather, Google Maps, Travel APIs

**Database:** SQLite (or other DBMS if configured)


## License
This project is licensed under the MIT License. See the LICENSE file for details.

