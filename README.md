# 🚀 PSG Attendance Tracker

A web application that automatically fetches and analyzes student attendance from the PSG eCampus portal and helps students understand how many classes they can **bunk** or **need to attend** to maintain the required **75% attendance**.

This project was built to make attendance tracking faster, clearer, and more useful for students compared to the traditional portal view.

---

## 🌐 Live Demo

🔗 https://att-frontend.vercel.app/

## 📂 GitHub Repository

🔗 https://github.com/vigneshviki19/AttendanceTrackerPSG

---

# ✨ Features

✅ Fetches **real attendance data** directly from the college portal
✅ Displays **subject-wise attendance percentage**
✅ Calculates how many classes you can **bunk or must attend**
✅ Shows **last updated attendance date** from the portal
✅ Modern **dark UI dashboard**
✅ Smart **bunk planner for each subject**
✅ Fast loading using backend **caching system**

---

# 🧠 How It Works

1. User enters **Roll Number & Password**
2. Backend logs into the **PSG eCampus portal**
3. Attendance page is scraped using **BeautifulSoup**
4. Data is processed and returned through a **Flask API**
5. Frontend displays:

   * Overall attendance
   * Subject-wise attendance
   * Bunk / Attend calculation

---

# 🛠 Tech Stack

### Backend

* Python
* Flask
* BeautifulSoup
* Requests

### Frontend

* HTML
* CSS
* JavaScript

### Deployment

* Vercel (Frontend)
* Render (Backend)

---

# 📊 Example Output

| Course | Subject                     | Attendance | Status               |
| ------ | --------------------------- | ---------- | -------------------- |
| 23O414 | Indian Constitution         | 57%        | 📚 Attend 12 classes |
| 23Z402 | Database Management Systems | 80%        | 😎 Bunk 3 classes    |
| 23Z404 | Theory of Computation       | 74%        | 📚 Attend 2 classes  |

---

# ⚡ Performance Optimization

To improve performance:

* Implemented **backend caching**
* Reused **PSG login session**
* Reduced repeated scraping requests

Result:

| Scenario       | Loading Time |
| -------------- | ------------ |
| Cold start     | ~5 sec       |
| Cached request | ~0.5 sec     |

---

# 📸 Screenshots

### Homepage

Login interface for checking attendance.

### Attendance Dashboard

Displays overall attendance and last updated date.

### Subject-wise Tracker

Shows attendance percentage and bunk planner.

---

# 🎯 Purpose of the Project

This project helped me learn:

* Web Scraping
* Backend API development
* Full-stack application design
* Deployment and caching techniques
* Performance optimization

It also solves a **real problem faced by students** when tracking attendance.

---

# 📬 Contact

For suggestions or improvements:

Instagram:
https://www.instagram.com/wikii._.15/

---

# ⭐ If you like this project

Give the repository a **star** and feel free to fork it!

---

# ⚠️ Disclaimer

This project is built **only for educational purposes**.
It simply automates publicly available information from the student portal.
