# 🎓 Face Recognition-Based Attendance System 👨‍💻

Automate your classroom or workplace attendance with cutting-edge AI!  
A feature-rich, web-based system combining **Face Recognition 🧑‍💻**, **Flask Web App** 🚀, **MySQL DB** 🗄️, and beautiful modern dashboards.

---

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python" />
  <img src="https://img.shields.io/badge/Flask-3.0-lightgrey?logo=flask" />
  <img src="https://img.shields.io/badge/OpenCV-4.10.0-brightgreen?logo=opencv" />
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" />
</p>

<p align="center">
  <img src="https://github.com/PatanFirozKhan/Face_Recognition-Based_Attendance_System/raw/main/static/demo.png" width="650" />
</p>

---

## 🚀 Why This Project?

- **Tired of roll calls?**  
- **Need secure, contactless attendance?**  
- **Want analytics, reports, and notifications?**

This project provides a plug-and-play solution for academic institutions, workplaces, and any group that needs seamless, accurate attendance tracking!

---

## ⭐️ Features

- **Facial Recognition:** Robust, reliable, and fast using OpenCV LBPH.
- **Real-Time Attendance:** Up to four daily punches (Early In, Late In, Lunch Out, Day Out).
- **Admin & Student Dashboards:** Control, monitor & report — all just a click away!
- **Automatic Email Reporting:** Daily attendance & grades delivered to your inbox.
- **Marks Management:** Enter, email, and view marks via clean interfaces.
- **Role-Based Access:** Secure logins and access levels for admin/students.
- **Modern UI:** Clean, responsive pages using Bootstrap & Jinja2.
- **REST API Support:** Data available as JSON for easy integration.
- **Fast Setup:** Up & running in minutes!

---

## 🗂️ Project Structure

```
Face_Recognition-Based_Attendance_System/
├── app.py               # 💡 Main application logic and endpoints
├── requirements.txt     # 📦 Python dependencies
├── sql.sql              # 🗄️ MySQL DB initialization
├── attendence-mail.html # 📧 Email template for attendance
├── marks-mail.html      # 📧 Email template for marks
├── Haarcascade/         # 🤖 Haarcascade classifier files
├── static/              # 🌆 Static resources (CSS, JS, images)
├── templates/           # 📄 HTML templates
├── TrainingImage/       # 🖼️ Training set images
├── test.py              # 🧪 Optional: tests
└── ...
```

---

## ⚙️ Quick Start

1. **Clone This Repo**
   ```bash
   git clone https://github.com/PatanFirozKhan/Face_Recognition-Based_Attendance_System.git
   cd Face_Recognition-Based_Attendance_System
   ```

2. **Install Dependencies**
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # or venv\Scripts\activate (Windows)
   pip install -r requirements.txt
   ```

3. **Configure Database**
   - Run `sql.sql` in your MySQL instance.
   - Set credentials in `app.py` if needed.

4. **Launch the App**
   ```bash
   python app.py
   ```
   or
   ```bash
   flask run
   ```

5. **Visit the App**
   - Browse to [http://localhost:3000](http://localhost:3000)

---

## 📸 Demo Screenshots

<p align="center">
  <img src="https://github.com/PatanFirozKhan/Face_Recognition-Based_Attendance_System/raw/main/static/screenshot1.png" width="320" />
  <img src="https://github.com/PatanFirozKhan/Face_Recognition-Based_Attendance_System/raw/main/static/screenshot2.png" width="320" />
</p>

---

## 🔑 Main Technologies

- **Python** 3.x
- **Flask** (Backend & Routing)
- **OpenCV** (Face recognition)
- **MySQL** (Data storage)
- **Pandas**, **scikit-learn** (Data analysis)
- **Bootstrap** (Modern UI)
- **SMTP** (Email reporting)

---

## 🏆 Key Highlights

- 💡 **100% automated attendance, fraud-proof**
- 📊 **Easy reporting with downloadable stats**
- 📬 **Instant email notifications**
- 🔒 **Privacy — no biometric data leaves your server**
- 🌎 **REST APIs for integration**

---

## 🤝 Credits & Inspiration

Based on the original work by [saiteja-4444](https://github.com/saiteja-4444/Face_Recognition-Based_Attendance_System), enhanced & modernized by **PatanFirozKhan**.

---

## 🤗 Contributing

Pull requests and feedback are welcome! Please create an issue for feature requests or bug reports.

---

## 📄 License

This repository inherits its license from the upstream repo. Check the license file before production/commercial use.

---

<p align="center">
  <b>Made with ❤️ by PatanFirozKhan</b>
</p>
