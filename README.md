# VITyarthi-
# 💊 Smart Medication Reminder System

A Python-based application that reminds users to take their medications on time.  
It stores medication schedules, triggers reminders, and logs medication history.

---

## 📌 Problem Statement

Elderly people and patients often forget to take medicines on time, which affects treatment efficiency. A system is required to:

- Remind users about medication schedules  
- Store medication details  
- Track taken/missed doses  

---

## 🎯 Objectives

- Notify users at the right time  
- Maintain a medication database  
- Log all reminder events  
- Provide simple command-line UI  

---

## 🔧 Technologies Used

- **Python 3**
- **JSON file storage**
- **Datetime module**
- **Threading for background reminder**
- **Platform notifications (ToastNotifier / Plyer)**

---

## 📁 Project Modules

### 1. **main.py**
Runs the app, allows adding medications & starting reminders.

### 2. **reminder.py**
Background scheduler that checks medicine times.

### 3. **database.py**
Handles medication storage (JSON file).

### 4. **notifier.py**
Shows system notifications.

### 5. **medication_data.json**
Stores medicines.

---

## ▶️ How to Run

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Start the application:

```
python main.py
```

---

## 📂 medication_data.json (Sample Format)

```json
[
  {
    "name": "Paracetamol",
    "time": "10:00"
  },
  {
    "name": "Vitamin D",
    "time": "18:30"
  }
]
```

---

## 🧪 Features

✔ Add new medicines  
✔ Automatic daily reminders  
✔ Persistent JSON storage  
✔ Cross-platform notifications  
✔ Reminder logs  

---

## 📘 Future Enhancements

- GUI using Tkinter  
- Mobile app integration  
- Voice alerts  
- Cloud backup  

---

## 👤 Author
This project was created as part of academic requirements.
Vedant Deshpande
