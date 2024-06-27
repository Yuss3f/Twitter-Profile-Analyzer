# Twitter Analytics Dashboard

## Project Description

Twitter Analytics Dashboard is a web application designed to help users visualize and analyze their Twitter account activities. Users can authenticate via Twitter OAuth, view their profile information, and gain insights into their tweet activity and engagement metrics.

## Features

- **Twitter OAuth Login**: Secure login using Twitter's OAuth authentication.
- **User Profile Display**: View detailed profile information fetched from Twitter.
- **Tweet Activity Visualization**: Interactive charts and graphs showing tweet activity over time.
- **Engagement Metrics**: Analysis of user engagement metrics like likes, retweets, and replies.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, React (optional)
- **Backend**: Python (Flask) / Node.js (Express)
- **Database**: MySQL
- **APIs**: Twitter API
- **Version Control**: Git, GitHub

## Setup and Installation

### Prerequisites

- Node.js and npm (for JavaScript backend)
- Python and pip (for Python backend)
- MySQL
- Git

### Clone the Repository

```bash
git clone https://github.com/yourusername/twitter-analytics-dashboard.git
cd twitter-analytics-dashboard

```

## Backend Setup

###Python (Flask) Backend

- Create a virtual environment and activate it:

```bash
	python -m venv venv
	source venv/bin/activate
```

- Install dependencies:

```bash
	pip install -r requirements.txt
```

- Set up environment variables for Twitter API credentials and MySQL database connection.
- Run the Flask server:

	flask run

### Node.js (Express) Backend

- Install dependencies:
```bash
	npm install
```

- Set up environment variables for Twitter API credentials and MySQL database connection
- Run the Express server:
```bash
	npm start
```

## Frontend Setup

