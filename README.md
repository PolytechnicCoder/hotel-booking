🏨 Hotel Booking System

🌍 Overview

This project is a Hotel Booking System built with Python and Pandas. It allows users to search for hotels, check availability, book reservations, and validate payments using a simulated credit card authentication system.

📌 Features

📋 View a list of available hotels.

✅ Book a hotel by entering its ID.

🏷️ Generate reservation tickets for customers.

🔐 Validate credit card details and authenticate transactions.

🛠 Technologies Used

Python

Pandas (for managing hotel and payment data)

CSV Files (for storing hotel and card information)


🚀 Installation & Setup

1️⃣ Clone the Repository:

git clone [CLICK](https://github.com/PolytechnicCoder/hotel-booking/tree/master)

2️⃣ Create a Virtual Environment:

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3️⃣ Install Dependencies:

pip install -r requirements.txt

4️⃣ Run the Application:

python main.py

📂 Project Structure

hotel-booking/
│── .venv/             # Virtual environment (ignored)
│── main.py            # Main booking system script
│── main2.py           # Alternative booking implementation
│── functions.py       # Helper functions (if applicable)
│── hotels.csv         # Hotel data
│── cards.csv          # Credit card details
│── card_security.csv  # Secure card authentication data
│── planning.txt       # Development notes
│── .gitignore         # Git ignored files

⚠️ Security Considerations

Remove card_security.csv before pushing the project publicly if it contains sensitive data.

Add .venv/ and .idea/ to .gitignore to avoid pushing unnecessary files.

Ensure cards.csv does not contain real credit card information.

🏨 Hotel Booking System - Built with Python & Pandas
