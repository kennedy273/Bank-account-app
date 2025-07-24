Kenya National Bank Streamlit App
Overview
The Kenya National Bank App is a simple web-based banking application built with Streamlit. It allows users to create a bank account, deposit funds, withdraw funds, and check their account balance. The application features a user-friendly interface and includes input validation to ensure secure and reliable transactions. Account numbers are auto-generated with a unique alphanumeric format, and all monetary transactions are displayed in Kenyan Shillings (KSH).
Features

Account Creation: Users can create a bank account by providing their name, with an automatically generated account number.
Deposit Funds: Add money to the account with validation for positive amounts.
Withdraw Funds: Withdraw money from the account, with checks for sufficient balance and valid amounts.
Check Balance: View the current account balance and account details.
Reset Option: Start over to create a new account.
Error Handling: Clear feedback for invalid inputs or transaction failures.

Prerequisites

Python 3.8 or higher
Streamlit (pip install streamlit)

Installation

Clone the Repository (if hosted on a version control system like GitHub):
git clone <repository-url>
cd kenya-national-bank-app


Install Dependencies: The application uses Python's standard libraries (random, string) and Streamlit. Install Streamlit using:
pip install streamlit


Verify Python Version: Ensure you have Python 3.8 or higher:
python --version



Usage

Run the Application: Navigate to the project directory and run the Streamlit app:
streamlit run banking_app.py


Access the App: Open your web browser and go to the URL provided by Streamlit (typically http://localhost:8501).

Interact with the App:

Create an Account: Enter your name and click "Create Account" to generate an account number and initialize your balance to KSH 0.00.
Perform Actions: Use the dropdown menu to select an action (Deposit, Withdraw, Check Balance).
Deposit: Enter a positive amount to add to your balance.
Withdraw: Enter an amount to withdraw, ensuring sufficient funds.
Check Balance: View your current balance and account details.


Start Over: Click the "Start Over" button to reset and create a new account.



File Structure
kenya-national-bank-app/
├── banking_app.py    # Main application code
├── README.md         # This README file

Deployment
To deploy the app on a platform like Streamlit Community Cloud (formerly Streamlit Sharing):

Push to GitHub: Ensure your code is in a GitHub repository.

Sign Up for Streamlit Community Cloud: Create an account at cloud.streamlit.io.

Deploy the App:

Connect your GitHub repository to Streamlit Community Cloud.
Specify banking_app.py as the main file.
Deploy the app and access it via the provided public URL.


Dependencies: Ensure a requirements.txt file is included if deploying externally:
streamlit



Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For questions or feedback, please contact the project maintainer at your-email@example.com.# Bank-account-app
