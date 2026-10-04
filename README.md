💸 Daily Expense

«A simple, aesthetic and lightweight expense tracker built with HTML, CSS & JavaScript.»

Daily Expense is a modern personal expense-tracking web app designed to make recording and understanding everyday spending quick and effortless.

No account. No backend. No complicated setup.
Just open the app and start tracking. ✨

---

✨ Features

- 💰 Today's Spending — Instantly see how much you've spent today.
- 📅 Monthly Overview — Track your total spending for the current month.
- ➕ Quick Expense Entry — Add an expense in seconds.
- 🏷️ Expense Categories — Food, Travel, Shopping, Bills, Entertainment, Health and Other.
- 📊 Weekly Spending Chart — Visualize your spending throughout the week.
- 🧾 Recent Expenses — View your latest transactions.
- 🗑️ Delete Expenses — Remove individual transactions whenever needed.
- 💾 Local Storage — Expenses are automatically saved in your browser.
- 📱 Responsive Design — Works on phones, tablets and desktops.
- 🌐 Offline Friendly — No backend or internet connection is required after loading the app.
- ⚡ Lightweight — Built with vanilla HTML, CSS and JavaScript.

---

🎨 Design

Daily Expense focuses on a clean and minimal interface rather than overwhelming the user with unnecessary features.

Design highlights

- Modern card-based interface
- Soft gradients
- Rounded UI elements
- Minimal typography
- Responsive mobile-first layout
- Simple expense workflow
- Visual weekly spending data

---

🛠️ Built With

Technology| Purpose
HTML5| Application structure
CSS3| UI, responsive design & styling
JavaScript| Application logic
LocalStorage API| Saving expenses locally
HTML5 Date & Number APIs| Dates and currency formatting

No frameworks or external libraries are required.

---

📂 Project Structure

Daily-Expense/
│
├── index.html
└── README.md

The entire application currently runs from a single HTML file.

---

🚀 Getting Started

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git

2. Open the project

cd YOUR-REPOSITORY

3. Run the app

You can simply open:

index.html

in your browser.

---

🖥️ Run With a Local Server

If you want to run it through a local server, you can use Python:

python -m http.server 8080

Then open:

http://localhost:8080

---

📱 Termux

You can also run Daily Expense directly from Android using Termux.

Install Python:

pkg install python

Navigate to the project folder:

cd ~/storage/downloads

Start the server:

python -m http.server 8080

Then open:

http://localhost:8080

---

💾 Data Storage

Daily Expense uses the browser's LocalStorage API.

Your expenses are stored locally on the device/browser:

Browser
   ↓
LocalStorage
   ↓
Daily Expense Data

There is currently no external database or server.

This means:

- ✅ No account required
- ✅ No backend required
- ✅ Fast and lightweight
- ✅ Works offline
- ⚠️ Clearing browser/site data can remove saved expenses
- ⚠️ Data is not automatically synchronized between devices

---

📊 Expense Categories

The app currently supports:

🍔 Food
🚕 Travel
🛍️ Shopping
💡 Bills
🎬 Entertainment
💊 Health
💳 Other

---

🔮 Future Improvements

Possible features for future versions:

- 🌙 AMOLED Dark Mode
- 📈 Advanced analytics
- 📊 Monthly & yearly charts
- 🔎 Search and filter transactions
- ✏️ Edit existing expenses
- 💰 Income tracking
- 🎯 Monthly budgets
- 🔔 Budget alerts
- 📤 Export to CSV
- 📄 Generate PDF reports
- ☁️ Cloud synchronization
- 👤 User accounts
- 🔐 PIN / biometric lock
- 📱 Installable PWA
- 🔄 Multi-device synchronization
- 🧠 Spending insights

---

🔒 Privacy

Daily Expense is designed with a local-first approach.

Your expense information is stored in your browser using LocalStorage and is not sent to an external server by the current version of the application.

---

🤝 Contributing

Contributions, ideas and improvements are welcome.

1. Fork the repository
2. Create a new branch

git checkout -b feature/new-feature

3. Make your changes
4. Commit your changes

git commit -m "Add new feature"

5. Push the branch

git push origin feature/new-feature

6. Open a Pull Request

---

⭐ Support

If you find Daily Expense useful, consider giving the repository a ⭐ on GitHub.

It helps support the project and encourages further development.

---

📄 License

This project is open source and available under the MIT License.

---

<div align="center">💸 Daily Expense

Track less. Understand more.

Made with ❤️ using HTML, CSS & JavaScript.

</div>
