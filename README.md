# 🎓 Orbit International School - Online Attendance & Student Management System

A modern, secure, and cloud-based web application designed for the teachers and administration of **Orbit International School**. This system allows teachers to easily manage student records, track monthly attendance sheets, and send instant WhatsApp alert messages to parents of absent students.

---

## ✨ Key Features

1. **Secure Teacher Login:** Teachers can securely log into the system using a designated username and password.
2. **Class Management (Play to Class 10):** Dedicated student lists for each class along with dynamic real-time total student counting.
3. **12-Month Digital Attendance Register:**
   * Track daily attendance (Present `P` / Absent `A`) from day 1 to 31 for every month.
   * Automatic calculation of total present and absent days per student.
   * Once attendance is saved, it automatically locks, with an option to enable an "Edit" mode if updates are needed.
4. **WhatsApp Alert System:** Easily send pre-formatted attendance warning messages directly to parents via WhatsApp when a student is absent.
5. **Secure SMS & Activity History:** A permanent history log of the last 20 sent actions detailing who sent the message, the recipient's number, and the message body, which cannot be deleted for security purposes.
6. **Responsive Dark UI:** A polished, modern dark-mode design fully optimized for mobile phones, tablets, and desktop computers.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6 Modules)
* **Backend & Database:** Google Firebase Firestore (Cloud Database)
* **Icons & Fonts:** Font Awesome 6.4.0, Google Fonts (Segoe UI)
* **Hosting / PWA:** Web App Manifest supported

---

## 📂 Project Structure

```text
📁 orbit-international-school/
│
├── index.html          # Main single-file application (HTML, CSS, and JavaScript integrated)
├── manifest.json       # Progressive Web App (PWA) manifest file
└── README.md           # Project documentation
