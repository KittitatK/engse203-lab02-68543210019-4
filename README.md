# 🚀 ENGSE203 LAB 02 — Modern JavaScript Dashboard

<p align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript)
![Vite](https://img.shields.io/badge/Vite-7.x-646CFF?logo=vite)
![Node.js](https://img.shields.io/badge/Node.js-v22-green?logo=node.js)
![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue?logo=github)

</p>

---

# 👨‍💻 Student Information

| รายการ | รายละเอียด |
|---------|------------|
| **ชื่อ-นามสกุล** | นาย กิตติทัต กันธรรม |
| **รหัสนักศึกษา** | 68543210019-4 |
| **Operating System** | macOS |
| **Repository** | `engse203-lab02-68543210019-4` |

---

# 📖 Project Overview

โปรเจกต์นี้เป็นส่วนหนึ่งของ **ENGSE203 - Modern JavaScript (Lab 02)**

พัฒนา Dashboard ด้วย **Modern JavaScript (ES Modules)** โดยแบ่งการทำงานออกเป็นหลายโมดูล เพื่อฝึก

- Modular Programming
- Reusable Code
- Maintainable Code
- Error Handling
- Fetch API
- GitHub Pages Deployment

Dashboard รองรับทั้ง

- ✅ Normal State
- ❌ Error State

---

# 🧩 Project Modules

| Module | Responsibility |
|---------|---------------|
| `api.js` | ดึงข้อมูลจาก `learning-tasks.json`, ตรวจสอบ HTTP Status, Validation และจำลอง Error |
| `main.js` | Entry Point, จัดการ State, Event Listener และ Error Handling |
| `ui.js` | Render UI ทั้งหมด พร้อมป้องกัน XSS ด้วย `escapeHtml()` |
| `utils.js` | Utility Functions เช่น Filter, Statistics และ Status Label |

---

# ⚙️ Installation

## Prerequisites

```bash
node -v
npm -v
```

ติดตั้ง Node.js ผ่าน NVM

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.5/install.sh | bash

source ~/.zshrc

command -v nvm

nvm install 22
nvm alias default 22
nvm use 22
```

Clone Project

```bash
git clone https://github.com/KittitatK/engse203-lab02-68543210019-4.git

cd engse203-lab02-68543210019-4

npm install
```

---

# 📂 Project Structure

```text
engse203-lab02-<student-id>/
│
├── public/
│   ├── .nojekyll
│   └── data/
│       └── learning-tasks.json
│
├── scripts/
│   └── check-project.mjs
│
├── src/
│   ├── api.js
│   ├── main.js
│   ├── style.css
│   ├── ui.js
│   └── utils.js
│
├── docs/
├── .gitignore
├── index.html
├── package.json
├── README.md
└── vite.config.js
```

---

# ▶️ Available Scripts

| Command | Description |
|----------|-------------|
| `npm install` | Install dependencies |
| `npm run dev` | Start Development Server |
| `npm run check` | Project Validation |
| `npm run build` | Build Production ไปยัง `docs/` |

หลังจากรัน

```bash
npm run dev
```

เปิด Browser ไปที่

```
http://localhost:5173
```

---

# 🌐 Live Demo

### GitHub Pages

🔗 https://kittitatk.github.io/engse203-lab02-68543210019-4/

---

# 📸 Screenshots

## ✅ Normal State

<img width="1891" height="962" alt="Screenshot 2026-07-12 1226111" src="https://github.com/user-attachments/assets/59f23a6f-91db-4709-9787-320096c45279" />

> Dashboard เมื่อโหลดข้อมูลสำเร็จ

🔗 https://kittitatk.github.io/engse203-lab02-68543210019-4/

---

## ❌ Error State

<img width="1913" height="818" alt="Screenshot 2026-07-12 123244" src="https://github.com/user-attachments/assets/20623c40-ecd0-440f-8817-f99982a6a5cb" />

> Dashboard เมื่อจำลองการเกิด Error

🔗 https://kittitatk.github.io/engse203-lab02-68543210019-4/?simulateError=1

---

# 🛠 Problems & Solutions

| Problem | Cause | Solution |
|---------|-------|----------|
| GitHub Pages ขึ้น 404 | ไม่ได้ Build ไปที่ docs | เพิ่ม `vite.config.js` และรัน `npm run build` |
| ใช้งาน Node 22 ไม่ได้ | ไม่ได้ Export PATH ของ NVM | เพิ่มคำสั่ง export ตามที่ NVM แจ้ง |

---

# 📚 References

-[async-await_and_error-handling.md](https://github.com/se-rmutl/engse203-lab/blob/main/labs/week-02-modern-javascript/docs/async-await_and_error-handling.md)
-[destructuring_array_map_filter_reduce.md](https://github.com/se-rmutl/engse203-lab/blob/main/labs/week-02-modern-javascript/docs/destructuring_array_map_filter_reduce.md)
-[functions_and_invocation.md](https://github.com/se-rmutl/engse203-lab/blob/main/labs/week-02-modern-javascript/docs/functions_and_invocation.md)
-[variable_naming.md](https://github.com/se-rmutl/engse203-lab/blob/main/labs/week-02-modern-javascript/docs/variable_naming.md)

---

# 🤖 AI Assistance

| รายการ | รายละเอียด |
|---------|------------|
| AI Tool | Gemini , ChatGPT |
| ใช้ช่วย | อธิบาย ES Modules, Debug Error, อธิบาย Function, ร่าง README |
| ผู้เรียนทำเอง | Source Code (`src`) และขั้นตอนการติดตั้งจากเอกสาร Lab |

---

# 📄 License

For educational purposes only.

ENGSE203 — Modern JavaScript Lab 02
