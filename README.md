# safe-return-
SafeReturn is a personal safety web application built using Python, Flask, and SQLite. It helps users monitor their journeys and remember to confirm their safe arrival.
# SafeReturn — Reached Safely?

## Features

- Start a journey by entering the destination, contact number, and expected arrival time.
- Store journey details in an SQLite database.
- Monitor journey deadlines using a background thread.
- Display a safety reminder when the expected arrival time is reached.
- Extend the journey deadline by 15 minutes.
- Confirm safe arrival and stop further reminders.
- Demonstrate an emergency SMS workflow.

## Technologies Used

- **Python** — application logic
- **Flask** — web framework and routes
- **SQLite** — database storage
- **HTML** — webpage structure
- **CSS** — webpage styling
- **Threading** — background journey monitoring

## How It Works

1. The user submits journey details through an HTML form.
2. Flask processes the form and stores the journey in SQLite.
3. A background monitor checks journey deadlines.
4. The application reminds the user to confirm safe arrival.
5. The user can confirm arrival or extend the journey.

## Running Locally

1. Install Python.
2. Create and activate a virtual environment.
3. Install the dependencies listed in `requirements.txt`.
4. Run the Flask application using `python app.py`.
5. Open the local address and port configured in the application.

## Current Limitations

Emergency SMS delivery depends on the configured implementation. A simulated SMS message does not send a real text message.

## Project Status

Developed as a learning project to practise Python, Flask, SQLite, HTML, CSS, and multithreading.
