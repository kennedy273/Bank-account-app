
# 🇰🇪 Kenya National Bank Streamlit Application

An interactive, web-based banking platform built with [Streamlit](https://streamlit.io/), simulating basic banking operations in a user-friendly Kenyan context.

---

## 💡 Project Overview

The **Kenya National Bank Streamlit Application** allows users to:

- Create a bank account with a unique account number
- Deposit and withdraw funds with validations
- Check their account balance
- Enjoy a smooth, beginner-friendly interface designed for learning and exploration

This app is perfect for those new to Python, object-oriented programming, and Streamlit.

---

## 🚀 Features

✅ **Account Creation**  
→ Enter a name to generate a 13-character account number (3-letter prefix from name + 10 random characters)

✅ **Deposit Funds**  
→ Add positive KSH amounts with validation for numeric and non-negative input

✅ **Withdraw Funds**  
→ Withdraw if sufficient funds exist, with real-time validation and feedback

✅ **Balance Inquiry**  
→ View current balance and account details

✅ **Session Persistence**  
→ Maintains data using Streamlit’s session state

✅ **Reset / Start Over**  
→ Allows starting afresh with a new account

✅ **Input Validation & Feedback**  
→ Green for success ✅, red for errors ❌

---

## 🛠️ Tech Stack

- **Python 3.8+** – Core language
- **Streamlit** – UI framework
- **Standard Libraries**:
  - `random` – Generate account numbers
  - `string` – Generate random characters

---

## 📦 Installation

### 🔧 Prerequisites
- Python 3.8 or higher
- Streamlit (`pip install streamlit`)

### 📥 Steps

```bash
# 1. Clone the Repository
git clone https://github.com/your-username/kenya-national-bank-app.git
cd kenya-national-bank-app

# 2. (Optional) Create Virtual Environment
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate

# 3. Install Dependencies
pip install -r requirements.txt
````

---

## ▶️ Usage

```bash
streamlit run banking_app.py
```

Access the app in your browser at: [http://localhost:8501](http://localhost:8501)

---

## 🧪 Example Workflow

1. Enter **"John Doe"** and create an account.
2. Deposit **KSH 1000.00**.
3. Withdraw **KSH 500.00** (Success ✅).
4. Try withdrawing **KSH 1000.00** (Failure ❌).
5. Check balance to confirm **KSH 500.00**.
6. Click **Start Over** to begin a new session.

---

## 🌐 Deployment (Streamlit Community Cloud)

1. Push your code to GitHub with:

   * `banking_app.py`
   * `requirements.txt`
   * `README.md`

2. Sign up at [Streamlit Cloud](https://streamlit.io/cloud)

3. Connect your GitHub repo, select `banking_app.py`, and deploy 🚀

---

## 📁 File Structure

```
kenya-national-bank-app/
├── banking_app.py        # Main Streamlit app
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## 🧪 Testing

### ✅ Manual Tests

* Create account with valid/invalid names
* Deposit/Withdraw positive, zero, negative, or text values
* Attempt withdrawal exceeding balance
* Test reset and session state

### 🔍 Edge Cases

* Letters instead of numbers for amounts
* Empty name input
* Confirm correct account number format: `ABCxxxxxxxxxx`

---

## 🤝 Contributing

Contributions welcome! Feel free to:

1. **Fork** the repo
2. **Create** a new branch:

   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Commit** your changes:

   ```bash
   git commit -m "Add your feature"
   ```
4. **Push** and **open a pull request**

Ideas:

* Add transaction history
* Improve UI/UX with custom themes
* Add login/authentication features

---

## 📄 License

Licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

Questions or suggestions?
Open an issue or email the maintainer at: `your-email@example.com`

---

## 🙏 Acknowledgments

* Built using [Streamlit](https://streamlit.io/)
* Inspired by basic banking system projects & Python learning paths

---

> *"Simulating Kenya’s banking simplicity for learning and beyond."*

```

---

Let me know if you want me to:
- Generate `requirements.txt` for you
- Help write the `banking_app.py` file
- Add badges (e.g., Streamlit Cloud badge, Python version)
- Create screenshots for visual appeal

Just say the word!
```
