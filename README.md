# College.Logs

> Your college life, logged.

College.Logs is a mobile-first college companion beginning with attendance management.

It helps students track attendance, understand their academic standing, and make better decisions about attending or missing classes.

The current HTML prototype serves as the validated product and UX foundation for the upcoming React Native application.

---

## ✨ Features

### 📊 Attendance Dashboard

- Overall attendance percentage
- Total attended and conducted classes
- Configurable attendance target
- Current attendance status
- Today's scheduled classes
- Quick attendance actions

### 📚 Subject Management

- Create subjects
- Edit subjects
- Delete subjects
- Add faculty information
- Set individual attendance targets
- View subject-specific attendance statistics

### ✅ Attendance Tracking

- Mark classes as Present or Absent
- Undo attendance actions
- Maintain attendance history
- Automatic attendance calculations

### 📅 Timetable

- Create weekly timetable entries
- Select subjects and days
- Set class start and end times
- Add room information
- View classes by day
- Prevent duplicate timetable entries
- Delete timetable entries

### 📈 Analytics

- Overall attendance analysis
- Attendance trends
- Subject risk analysis
- Identify subjects requiring attention
- Attendance distribution
- What-if attendance calculations

### 🧮 Attendance Decision Support

College.Logs goes beyond displaying percentages.

It helps answer questions such as:

- Can I miss the next class?
- How many classes do I need to attend to reach my target?
- What will my attendance become if I miss additional classes?
- Which subjects currently require the most attention?

### 📜 Attendance History

- View attendance records by date
- Group records chronologically
- View subject-specific history
- Edit or remove historical records

### ⚙️ Settings

- Change default attendance target
- Manage timetable
- Reset demo data
- Delete all application data
- View application information

### 💾 Local Persistence

The current prototype uses browser LocalStorage to persist:

- Subjects
- Attendance records
- Timetable entries
- Attendance targets
- Onboarding information
- User settings

No backend or external database is required for the current prototype.

---

## 🚀 Getting Started

The current prototype is a standalone HTML application.

### Requirements

A modern web browser such as:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

### Run locally

Clone the repository:

```
git clone https://github.com/NTgGamer1/college-logs.git
```

Open the project directory:

```
cd college-logs
```

Then open `college-logs.html` in your browser.

No build system, package manager, backend, or API configuration is required for the current prototype.

---

## 🧭 Application Structure

```
College.Logs
│
├── Onboarding
│   ├── Welcome
│   ├── User setup
│   └── Attendance target
│
├── Home
│   ├── Overall attendance
│   ├── Today's classes
│   └── Attendance status
│
├── Subjects
│   ├── Subject list
│   ├── Add subject
│   ├── Edit subject
│   └── Subject details
│
├── Analytics
│   ├── Overall statistics
│   ├── Attendance trends
│   ├── Risk analysis
│   └── What-if calculations
│
├── Timetable
│   ├── Weekly schedule
│   ├── Add class
│   └── Delete class
│
├── History
│   └── Attendance records
│
└── Settings
    ├── Default target
    ├── Timetable management
    ├── Demo data
    └── Data reset
```

---

## 🎯 Product Philosophy

College.Logs is built around three principles:

### 1. Simple

Attendance should take only a few seconds to record.

### 2. Actionable

A percentage alone is not enough.

Students should understand what that percentage means and what they can do next.

### 3. Student-first

The application is designed around real student questions and workflows rather than administrative attendance management.

---

## 🧠 Attendance Logic

College.Logs calculates attendance using:

```
Attendance % = (Classes Attended / Total Classes) × 100
```

The application also calculates:

- Current attendance status
- Classes that can be missed while maintaining the target
- Classes required to recover to the target
- Hypothetical attendance after additional absences
- Subject risk levels

Subjects can be classified based on their relationship with the configured attendance target.

---

## 🏗️ Current Technology

The current prototype is intentionally lightweight.

```
HTML
CSS
JavaScript
LocalStorage
```

There is currently no:

```
Backend
Database
Authentication
External API
AI API
```

The architecture will evolve as College.Logs moves toward the React Native implementation.

---

## 📱 Future Direction

The HTML prototype is not intended to be the final application architecture.

It acts as the product and UX foundation for the next stage of development.

The next major milestone is a React Native application that will preserve the validated product experience while providing a maintainable mobile architecture.

---

## 🗺️ Development

### Current Milestone

**HTML Prototype — Completed ✅**

The prototype establishes the core College.Logs experience, including:

- Attendance tracking
- Subject management
- Timetable management
- Analytics
- Attendance history
- Attendance decision-support calculations
- Onboarding
- Local persistence

### Next Milestone

**React Native Application — Next ⏳**

The next stage is to translate the validated prototype into a maintainable React Native architecture while preserving the core product experience and improving reliability, usability, and scalability.

For the complete development roadmap, milestones, implementation stages, and project progression, see:

**[`DEVELOPMENT.md`](DEVELOPMENT.md)**

---

## 🤖 AI-Assisted Development

College.Logs is developed with the assistance of AI tools.

AI assistance may be used for areas such as:

- Code generation
- Prototyping
- Debugging
- Documentation
- UX exploration
- Development support

Product direction, requirements, decisions, testing, review, iteration, and final implementation choices remain human-directed.

---

## 📄 License

College.Logs is released under the **MIT License**.

See [`LICENSE`](LICENSE) for the complete license text.

---

## 👤 Project

**College.Logs**

Created by **_NtgGamer1_** : **Nikhil Maurya**

GitHub:
https://github.com/NTgGamer1/college-logs
