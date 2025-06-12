## 📘 PopX Landing React App

A pixel-perfect React.js application based on an Adobe XD design, featuring smooth navigation between screens (Landing, Signup, Login, and Profile). Built using **React**, **CSS**, and **React Router DOM**.

---

### 📌 Features

- 🔹 Pixel-perfect responsive layout
- 🔹 Navigation:

  - Signup → Login → Profile

- 🔹 Static profile page UI based on design
- 🔹 Clean CSS (no Tailwind used)
- 🔹 No external state management or backend

---

### 🛠️ Tech Stack

- **React.js**
- **React Router DOM**
- **CSS**

---

### 📁 Folder Structure

```
popx-landing/
│
├── public/
│   └── index.html
│
├── src/
│   ├── components/
│   │   ├── Landing.jsx
│   │   ├── Signup.jsx
│   │   ├── Profile.jsx
│   │   └── Login.jsx
│   │
│   ├── styles/
│   │   ├── Landing.css
│   │   ├── Signup.css
│   │   ├── Profile.css
│   │   └── Login.css
│   │
│   ├── index.js
│   └── App.js
│
├── package.json
└── README.md
```

---

### 🚀 How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/aliabrar21/Educase.git
   cd my-react-app
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm start
   ```

4. **View in browser:**

   ```
   http://localhost:3000
   ```

---

### 🔗 Page Flow

1. **Landing Page** (`/`)
   → Click **Create Account** → navigates to `/signup`
   → Click **Already Registered? Login** → navigates to `/login`

2. **Signup Page** (`/signup`)
   → On submit → navigates to `/login`

3. **Login Page** (`/login`)
   → On successful login → navigates to `/profile`

4. **Profile Page** (`/profile`)
   → Static design with Account Settings and user info

---

### 📸 Adobe XD Design Reference

Used reference screens from Adobe XD for pixel-perfect implementation.

---

### 📦 Dependencies

```bash
npm install react-router-dom
```

---

### 👨‍💻 Author

**Gaurav Mehra**
Frontend Developer (React.js)
Location: Delhi, India
