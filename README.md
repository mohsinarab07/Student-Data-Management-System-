# Student-Data-Management-System with Api integration -


A simple and efficient **Student Management System** built using **React** with API integration (json-server). This project helps manage student data such as creating, reading, updating, and deleting student records.

---

## 🚀 Features

* Add new students
* View student details
* Update existing student information
* Delete students
* API integration using **json-server**
* Clean UI with responsive layout

---

## 📂 Project Structure

```
/Student-Management-System
│── /src
│   ├── App.js
│   ├── StudentTable.js
│   ├── CreateStudent.js
│   ├── EditStudent.js
│   ├── ViewDetails.js
│   └── App.css
│
│── db.json
│── package.json
│── README.md
```

---

## 🛠️ Tech Stack

* **Frontend:** React JS
* **Backend / API:** json-server
* **Routing:** react-router-dom

---

## ⚙️ How to Run the Project

### 1. Install Dependencies

```
npm install
```

### 2. Start React App

```
npm start
```

### 3. Start json-server

```
npx json-server --watch db.json --port 8000
```

The API will run at:

```
http://localhost:8000/students
```

---

## 📝 API Endpoints

| Method | Endpoint      | Description        |
| ------ | ------------- | ------------------ |
| GET    | /students     | Get all students   |
| GET    | /students/:id | Get single student |
| POST   | /students     | Add new student    |
| PUT    | /students/:id | Update student     |
| DELETE | /students/:id | Delete student     |

---

## 🌐 Deployment

To deploy manually on GitHub Pages:

1. Build project

```
npm run build
```

2. Upload the `build` folder files manually to your GitHub repository
3. Enable GitHub Pages from **Settings → Pages → Deploy from branch → /root (build folder)**

---

## 📄 Custom Deployment URL

Your GitHub Pages URL will be:

```
https://mohsinarab07.github.io/Student-Data-Management-System/
```

---

## 🙌 Author

**Mohsin Arab**

Feel free to contribute, report issues, or suggest improvements!
