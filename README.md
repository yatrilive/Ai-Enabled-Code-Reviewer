Project Title and Description:
AI-Enabled Code Reviewer
A MERN stack application that reviews code snippets for quality, performance, and security using AI, helping developers improve their coding standards.


Features:
Real-time code review and suggestions.
History of previous code reviews.
Syntax highlighting and markdown support.


Tech Stack:
Frontend: React, Vite, CSS, react-simple-code-editor, prismjs
Backend: Node.js, Express, MongoDB
AI Service: Integrates with an AI model for code analysis.


Getting Started:


Prerequisites: Node.js, MongoDB


Installation:
bash
Copy
Edit
# Clone the repository
git clone https://github.com/yatrilive/Ai-Enabled-Code-Reviewer.git

# Navigate to backend and install dependencies
cd code-review/BackEnd
npm install

# Start the backend server
npm start

# In a new terminal, navigate to frontend and install dependencies
cd ../Frontend
npm install

# Start the frontend development server
npm run dev


Environment Variables:
Create a .env file in the backend directory and add the following:
env
Copy
Edit
MONGO_URI=your_mongodb_connection_string
PORT=5000


Usage:
Enter your code in the editor and click "Review" to get AI-generated feedback.
View previous reviews by expanding the "Previous Searches" list.


Screenshots:
![image](https://github.com/user-attachments/assets/91969770-3b90-4948-86b0-5d95b3e73520)
![image](https://github.com/user-attachments/assets/33453975-a4c9-4fdb-9d56-523b1b3b8181)
![image](https://github.com/user-attachments/assets/ffc5c67b-26a5-4c6b-bb00-bfc454e5035b)
![image](https://github.com/user-attachments/assets/48fee5c1-3a4f-4ca8-a7d1-72d067d510f5)






API Endpoints:
POST /ai/get-review: Submits code for review.
GET /ai/previous-searches: Fetches a list of previous searches.


Contributing:
Contributions are welcome!
Fork the repository, create a new branch, and submit a pull request.


Contact:
Developed by Sarvesh Kumar Pandey - https://www.linkedin.com/in/sarveshkpandey/
