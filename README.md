# 🔐 Password Manager

A simple and user-friendly Password Manager built with Python and Tkinter. This desktop application allows you to generate strong, random passwords and securely store them locally for future use.

## 🚀 Features

- ✅ Generate secure passwords with letters, numbers, and symbols
- ✅ Automatically copy generated passwords to the clipboard
- ✅ Store website login details (website, email, password) locally
- ✅ Simple and intuitive graphical user interface (GUI) using Tkinter

---

## 🛠️ How It Works

1. **Enter Website & Email/Username**
2. **Click “Generate Password”** to create a strong random password
3. **Click “Add”** to save the details to a local `data.txt` file
4. The password is also copied to your clipboard automatically

---

## 📁 File Structure

password-manager/
│
├── logo.png # App logo used in the GUI
├── data.txt # (Generated) Stores saved login details
└── main.py # Main Python source code

---

## 💡 Getting Started

### Prerequisites

Please ensure you have Python installed. You also need the following packages:

- `tkinter` (comes with Python)
- `pyperclip`

To install `pyperclip`, run:

```bash
pip install pyperclip
Running the App
Clone the repo and run the app:

git clone https://github.com/your-username/password-manager.git
cd password-manager
python main.py

---
📌 Notes
Your passwords are stored locally in a plain text file, data.txt. For better security, consider encrypting the file or integrating with a secure vault system.

Update the default email inside the code or allow user settings for flexibility.

---

✨ Future Improvements
Search saved credentials

Edit or delete saved passwords

Store data in an encrypted format

Add login authentication to access the password manager

---

📄 License
This project is open source and available under the MIT License.

🙌 Acknowledgements
Python & Tkinter Docs

Pyperclip

Made with ❤️ by Abdulganiyu_Techie
