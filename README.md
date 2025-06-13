# 🏥 Hospital Queue Management System (Java Swing GUI)

This is a **Java Swing-based GUI application** that simulates a hospital queue management system. It uses core Java data structures like `PriorityQueue`, `List`, and OOP principles to manage patient records based on their severity.

---

## 🚀 Features

- Add patients with details: Name, Age, Disease, Severity
- Prioritize patients based on severity (1 to 5, where 5 is most severe)
- Call and discharge the next patient in line
- Search for patients by name and age
- View the full queue and discharged patient list
- Simple and responsive GUI using Java Swing

---

## 🧠 Core Concepts Used

- **Object-Oriented Programming**: Classes like `Patient`, `HospitalQueueManager`, and `HospitalGUI`
- **Data Structures**:
  - `PriorityQueue` – for ordering patients based on severity
  - `ArrayList` – to store discharged patients
- **Java Swing** – GUI components (JFrame, JButton, JTable, JTextField, etc.)
- **Event-Driven Programming** – handling user interactions

---

### 🛠 Requirements

- Java JDK 8 or higher
- Any IDE (e.g. IntelliJ, Eclipse) or command line

### 💡 Steps

1. Clone or download the repository.
2. Compile all `.java` files:

3. Run the main GUI class:

 <pre>java HospitalGUI</pre> 

### 🖥️ Main GUI Interface

![Hospital Queue GUI](https://github.com/user-attachments/assets/b6a97c5f-5feb-45f7-87a6-ece3fd93816f)

---

## 📌 Notes

- 🔢 **Severity system**: Patients with lower severity values are treated first (`1` is highest priority).
- 💾 **Data storage**: All data is stored **in-memory**. Restarting the app will clear the queue.

---

## 📬 Future Enhancements

- 💽 Save/load patient data using files or a local database
- 🔐 Add login functionality for doctors/admins
- 🌐 Extend with REST API or a web-based frontend (e.g. using Flask or React)

---

## 🧑‍💻 Author

**Yasir Sheikh**  
Built as a practice project to demonstrate Swing GUI, Java Collections Framework, and priority-based patient queueing logic.

---

## 📝 License

This project is open-source and available under the **MIT License**.

