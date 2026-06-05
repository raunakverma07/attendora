# 🎓 AttendX — Smart Attendance System

> A modern, professional attendance management web app built for college classrooms. No installation, no database, no backend — just open the link and start.

![AttendX](https://img.shields.io/badge/AttendX-v1.0-63b3ed?style=for-the-badge&logo=graduation-cap)
![Built With](https://img.shields.io/badge/Built%20With-React%20%2B%20HTML-4fd1c5?style=for-the-badge)
![License](https://img.shields.io/badge/License-Free%20Forever-48bb78?style=for-the-badge)
![Made By](https://img.shields.io/badge/Made%20by-Raunak-fc8181?style=for-the-badge)

---

## ✨ What is AttendX?

AttendX was built to solve a real classroom problem — teachers spending valuable time on manual attendance registers. This app brings the entire process online, making it **faster, smarter, and accessible to everyone** from any device.

---

## 🚀 Live Demo

🔗 **[Open AttendX →](https://your-site.netlify.app)**

> Replace the link above with your Netlify URL after deploying.

---

## 📸 Features at a Glance

| Feature | Description |
|---|---|
| 🎯 Smart Attendance | Checkbox-based — all students default to absent. Mark present, save. Done in under 60 seconds for 100+ students |
| 🏖️ Holiday Marking | Mark any date as holiday — automatically excluded from % calculation for everyone |
| 📊 Colour Grading | Every student gets an auto colour grade based on their attendance % |
| 📅 Date Search | Search any specific date to see who was present, absent, or if it was a holiday |
| ➕ Add Anytime | Add new students mid-semester without affecting existing records |
| 🔄 Move Students | Move a student to a different class in one tap |
| 🔐 Student Self-Check | Students check their own % using class code + name. No login needed |
| 💾 Auto-Save | All data saved in browser's localStorage — persists across sessions |
| 📱 Works Everywhere | Any phone, tablet, or laptop. No installation required |

---

## 🎨 Attendance Colour Grading System

| Grade | Range | Meaning |
|---|---|---|
| 🟢 **Safe** | 85% and above | Regular attendance. No action needed |
| 🟡 **Average** | 65% – 84% | Attendance slipping. Keep an eye |
| 🟠 **Danger** | 40% – 64% | Needs immediate attention |
| 🔴 **Critical** | Below 40% | Action required urgently |

---

## 🧑‍🏫 How to Use — For Teachers

1. **First Time Setup** — Click *"New Teacher? Create Account"*, enter your name, create a Teacher ID & password. One-time only.
2. **Create a Class** — From your dashboard, click *"+ New Class"*. A unique 6-character class code is auto-generated.
3. **Add Students** — Open class → Students tab → add names one by one. Add more anytime.
4. **Take Daily Attendance** — Attendance tab → pick date → tick present students → Save. All absent by default.
5. **Mark Holidays** — In Attendance tab, tap *"Mark Holiday"*. That day won't count in anyone's % automatically.
6. **View Reports** — Summary tab shows each student's % with colour grade. Date Search lets you look up any specific date.

---

## 🎓 How to Use — For Students

1. **Get your class code** from your teacher (looks like `AB12CD`)
2. Open the link → click **"Student — Check My Attendance"**
3. Enter your class code and your full name (exact, as registered)
4. Your attendance %, colour grade, and full date-by-date history appears instantly

> 💡 Students don't need an account or password — just the class code + name.

---

## 🛠️ Tech Stack

```
Frontend     →  React 18 (via CDN, no build step)
Styling      →  Inline CSS + Google Fonts (Syne, DM Sans)
Storage      →  Browser localStorage (no backend needed)
Hosting      →  Netlify (free tier)
```

---

## 📁 Project Structure

```
attendx/
│
└── attendx.html        # Entire app in one file — React + CSS + JS
└── README.md           # This file
```

---

## ⚡ Deploy Your Own (5 Minutes)

1. **Fork or download** this repository
2. Go to [netlify.com](https://netlify.com) → Sign up free
3. Drag & drop the `attendx.html` file onto Netlify
4. Your live link is ready — share it with your students!

---

## 💡 Important Notes

- **Data is stored in the browser** (localStorage). It persists across sessions on the same device and browser.
- If the teacher clears browser cache or switches devices, data will reset. A backup/export feature may be added in future.
- This app is designed for **single-teacher use per device** currently.

---

## 🔮 Planned Features (Coming Soon)

- [ ] Export attendance data as Excel/CSV
- [ ] Multiple teacher support
- [ ] PWA support (install as app on phone)
- [ ] Dark/Light theme toggle
- [ ] Print-ready attendance sheet

---

## 👨‍💻 About the Developer

**Raunak**
B.Sc Computer Science Student
Holkar Science College, Indore

> *"I built AttendX to help my teachers — and hopefully yours too."*

**Skills & Interests:**
`Python` `Data Science` `Machine Learning` `Deep Learning` `GenAI` `Web Development`

---

## 📄 License

This project is free to use, modify, and share.
Built with ❤️ for teachers everywhere.

---

<div align="center">

**⚡ Crafted by Raunak · Holkar Science College · 2026**

*AttendX — Attendance Management, Reimagined.*

</div>
