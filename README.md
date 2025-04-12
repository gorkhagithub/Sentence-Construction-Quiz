📚 Sentence Construction Quiz
An interactive educational tool designed to help users practice sentence construction by filling in blanks with the correct words.

✨ Features
🧠 Interactive sentence completion exercises

⏱️ 30-second timer for each question

🧩 Word selection and blank-filling mechanism

📊 Real-time score tracking and feedback system

📱 Responsive design for all device sizes

🛠️ Setup Instructions
✅ Prerequisites
Node.js and npm installed

JSON Server (for mock API)

🚀 Installation
Clone the repository

bash
Copy
Edit
git clone <repository-url>
cd sentence-construction-quiz
Install dependencies

bash
Copy
Edit
npm install
Install JSON Server

bash
Copy
Edit
npm install -g json-server
Add question data
Create a db.json file in the root directory with your question data
(or download it from the provided link if available)

Run JSON Server (in a separate terminal)

bash
Copy
Edit
json-server --watch db.json
Start the development server

bash
Copy
Edit
npm run dev
Open the app
Visit: http://localhost:8080

🕹️ How to Play
Each question shows a sentence with missing words

Choose the correct words from the given options

Click on blanks to replace or remove words

Complete the sentence within 30 seconds

Press "Next" to go to the next question

Get your score and feedback at the end

🧰 Technologies Used
React

TypeScript

Tailwind CSS

shadcn/ui

🙌 Credits
Developed by Abhishek Gorkha