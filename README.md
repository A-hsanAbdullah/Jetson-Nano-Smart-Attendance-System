## Jetson Nano Smart Attendance System

### Project Overview
This project involves developing a Smart Attendance System using the **Jetson Nano** with **Edge Computing** capabilities. The system leverages **Face Recognition** technology to automate attendance marking and enhance security measures.

### Key Steps & Implementation:
1. **Jetson Nano Setup:**
   - Installed **JetPack** on Jetson Nano.
   - Configured **headless setup** via **remote desktop connection** (using IP address) as no display was available.

2. **Python & Libraries Installation:**
   - Installed **Python 3** and the following libraries:
     - OpenCV
     - Numpy
     - Pandas
     - PIL (Pillow)
     - Tkinter (for GUI development)

3. **Face Detection & Recognition:**
   - Utilized **Haar Cascade Classifier** (`haarcascade_frontalface_default.xml`) for face detection.
   - Implemented **Face Recognition Model** using **Local Binary Patterns Histogram (LBPH)**.
   - Trained the model and generated `trainer.yml` file for face recognition.

4. **Attendance Management System:**
   - Built a **Graphical User Interface (GUI)** using **Tkinter**.
   - Integrated **Pandas** to record attendance data in an **Excel Sheet (.csv/.xlsx)**.
   - Marked students as **Late** based on check-in time.

5. **Additional Applications:**
   - Potential to extend the system for **Security Applications** such as **theft detection** or **criminal identification**.

### Technical Details:
- **Machine Learning Model:** **LBPH (Local Binary Patterns Histogram)**
- **Face Detection Algorithm:** **Haar Cascade Classifier**
- **Output File:** `trainer.yml` (Stores trained face recognition data)
- **Data Storage:** Attendance records saved using **Pandas DataFrame** in **Excel (.csv/.xlsx)** format.

### Skills Demonstrated:
- **Computer Vision**
- **Machine Learning (LBPH Model)**
- **Face Recognition & Detection**
- **Edge Computing**
- **Python Development**
- **Data Handling with Pandas**
- **GUI Development with Tkinter**
- **Embedded Systems Setup (Jetson Nano)**

### Fields Covered:
- **Artificial Intelligence**
- **Machine Learning**
- **Computer Vision**
- **Edge Computing**
- **Embedded Systems**
- **Software Development**
- **Automation**

### Documentation:
All commands and installation steps are detailed in the provided documentation file within the repository.

