# 🔐 Authentication Project

This is a full-stack **user authentication system** built with **Django (backend)** and **Vue.js (frontend)**. It supports secure login, registration, email-based password reset, and password change functionalities.

---

## 📸 Screenshots & Features

### 🚪 Login Page

Users can securely log in using their **email and password**. On successful login, a JWT token is generated for secure backend communication.

![Login Page](https://github.com/user-attachments/assets/52c9599b-5129-4b31-9247-4dc8a952e6b2)

---

### 📝 Register Page

New users can create an account by providing a valid email and strong password. Password strength and duplicate email validation are handled server-side.

![Register Page](https://github.com/user-attachments/assets/3c2d40a0-10a1-4abe-abc9-055d036ba6c0)

---

### 🔑 Reset Password Page

If a user forgets their password, they can request a reset link to be sent to their registered email address.

![Reset Password](https://github.com/user-attachments/assets/93497a80-b382-41f0-9e24-71aa50709ac4)

---

### 📧 Email Sent Confirmation

Once the user submits a valid email, a password reset link is sent with a secure token. This screen confirms that the email has been dispatched.

![Email Sent](https://github.com/user-attachments/assets/f4222c31-1b6a-484e-9ea6-5b58c4f93ed3)

---

### 🔄 Change Password Page

Using the link received in the email, users can set a new password. The token ensures that only the intended user can access this page.

![Change Password](https://github.com/user-attachments/assets/c50a828a-1ee0-4c4b-b540-31219755ed75)

---

### ✅ Password Successfully Changed

After setting a new password, the user sees a confirmation page and can proceed to log in with the updated credentials.

![Password Changed](https://github.com/user-attachments/assets/3e39d51f-c43a-4b76-9630-b552718bbbcb)

---

## ⚙️ Features Overview

- 🔐 **User Authentication** (Login, Logout)
- 📝 **User Registration**
- 🔁 **Password Reset Workflow** via Email Token
- 📧 **Email Notification** for Password Reset
- 🔒 **JWT Authentication** for API security
- 📱 **Responsive UI** built with Vue.js

---

## 🧰 Tech Stack

| Layer       | Technology             |
|-------------|-------------------------|
| Frontend    | Vue.js                  |
| Backend     | Django + Django REST    |
| Auth System | JWT (Simple JWT)        |
| Email       | SMTP (e.g., Gmail)      |
| Database    | SQLite / PostgreSQL     |

---

## 🛠️ Project Setup

### 🔧 Backend (Django)

```bash
# Step 1: Clone the repository
git clone https://github.com/your-username/Authentification_project2.git
cd Authentification_project2/backend

# Step 2: Setup virtual environment
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate

# Step 3: Install dependencies
pip install -r requirements.txt

# Step 4: Run migrations
python manage.py migrate

# Step 5: Start backend server
python manage.py runserver





