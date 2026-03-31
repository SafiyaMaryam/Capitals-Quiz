🌍 Capital Quiz App

A dynamic and interactive Capital Quiz web application that tests users' knowledge of world capitals. Built using Node.js, Express, JavaScript, and PostgreSQL, this app provides a fun way to learn geography while tracking performance.

🚀 Features:

🧠 Quiz users on countries and their capitals
📊 Score tracking system
🔄 Randomized questions for each attempt
💾 Data stored and managed using PostgreSQL
⚡ Fast and responsive backend with Express

🛠️ Tech Stack:

Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express
Database: PostgreSQL

📂 Project Structure:

capital-quiz/
│── public/          # Static files (CSS, JS)
│── views/           # Templates (EJS/HTML)
│── db/              # Database setup/config
│── app.js           # Main server file
│── package.json

⚙️ Installation & Setup:

Clone the repository
git clone https://github.com/your-username/capital-quiz.git
cd capital-quiz
Install dependencies
npm install
Set up PostgreSQL database
Create a database
Add your credentials in the project config file
Run the application
node app.js
Open in browser:
http://localhost:3000

🧩 How It Works:

The server fetches quiz questions from the PostgreSQL database
A country is displayed, and the user enters the capital
The app validates the answer and updates the score
Results are displayed instantly

📌 Future Improvements
Add difficulty levels
Timer-based quiz mode
Leaderboard system
UI enhancements
🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

📜 License:

This project is open-source and available under the MIT License.
