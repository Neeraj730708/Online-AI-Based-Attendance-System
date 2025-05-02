# AI-Powered Smart Attendance System with Performance Analysis

## 📌 Project Overview
This project is an **AI-powered Smart Attendance System** that leverages **face recognition** to automate attendance marking. It ensures efficient tracking, prevents duplicate entries within an hour, and provides an **attendance analysis report**. The analysis uses **A* algorithm** to determine how many more days a student needs to attend to reach the average attendance percentage.

## ✨ Features
- **Face Recognition-Based Attendance** 📸
- **Prevents Duplicate Marking** (1-hour interval check) ⏳
- **Attendance Report Generation** 📊
- **Analysis using A\* Algorithm** 🧠
- **Prediction of Required Attendance for Improvement** 🔍

## 🛠️ Tech Stack
- **Python** 🐍
- **OpenCV** 👀
- **Face Recognition** 🏷️
- **CSV for Data Storage** 📄
- **A\* Algorithm for Analysis** ⚡

## 🚀 Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/arunpwr2712/AI-Powered-Smart-Attendance-System-with-Performance-Analysis.git
   cd AI-Powered-Smart-Attendance-System-with-Performance-Analysis
   ```
2. Install dependencies:
   ```bash
   pip install opencv-python numpy face-recognition
   ```
3. Run the program:
   ```bash
   python main.py
   ```

## 📝 Usage
1. **Mark Attendance:**
   - The system captures the face and records attendance if 1 hour has passed since the last marking.
2. **Generate Attendance Report:**
   - Analyzes attendance percentage and predicts required attendance using A* algorithm.
   - Generates `attendance_report.csv` with details.

## 📊 Example Output
```bash
Attendance Report:
John Doe: 80.00% attendance
Jane Smith: 65.00% attendance

Jane Smith needs to attend 3 more days to reach the average attendance of 75%.
```

## 📂 File Structure
```
├── main.py  # Main attendance script
├── face_recognition_module.py  # face recognition script
├── attendance.py  # attendance marking script
├── analysis.py  # A* Analysing script
├── Students/images  # Student data (images)
├── attendance.csv        # Stores attendance records
├── attendance_report.csv # Stores attendance analysis
├── README.md             # Project Documentation
```

## 📌 Future Enhancements
- **Database Integration** (MySQL / Firebase)
- **Web Dashboard for Attendance Tracking**
- **Real-time Notification System** 📩

## 📜 License
This project is **open-source** under the MIT License.

## 🤝 Contributing
Feel free to fork, contribute, or raise issues to improve the system! 🚀

---
⭐ **Star this repository** if you find it useful! 😃

