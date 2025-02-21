Login & Dashboard System

This project is a simple login authentication system using HTML, CSS, Bootstrap, and JavaScript. It includes a login page (index.html) and a protected dashboard (dashboard.html).

📌 Features

Login Page

Accepts admin credentials to allow access

Shows error message for incorrect login

Redirects to dashboard.html upon successful login

Dashboard Page

Displays a banner image and a photo gallery (4 columns, 5 rows)

Protects access by checking login session

Includes a logout button to return to the login page

🚀 How It Works

User enters credentials in index.html

If login is successful, session is stored in sessionStorage

User is redirected to dashboard.html

If dashboard.html is accessed directly without logging in, it redirects back to index.html

Clicking logout clears the session and returns to index.html

🛠 Technologies Used

HTML (Structure)

CSS & Bootstrap (Styling & Layout)

JavaScript (Login validation & Session handling)

📂 Project Structure

📁 project-folder/
│── index.html (Login Page)
│── dashboard.html (Protected Dashboard)
│── README.md (Documentation)

🔑 Default Admin Credentials

Username: admin

Password: 12345

📜 Usage

Open index.html in a browser

Enter the admin username & password

After successful login, you will be redirected to dashboard.html

Click the Logout button to return to the login page

❗ Important Notes

sessionStorage is used for session management (it will be cleared when the tab is closed)

You can modify the default credentials in index.html (inside the checkLogin function)

💡 Future Improvements

Use localStorage or cookies for persistent login

Implement server-side authentication using PHP / Node.js

Add database storage for user credentials
