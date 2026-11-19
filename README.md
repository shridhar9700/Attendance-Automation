# AI-Powered Attendance Automation System

> **Not every impactful project needs another website. Sometimes, the best innovation is solving a real-world problem through automation.**

### About the Project

Teachers often spend valuable time transferring absent students' roll numbers from handwritten attendance sheets into college ERP systems.

This project simplifies that process by combining **OCR and browser automation** to convert handwritten attendance records into digital entries and automatically update the ERP portal.

The goal is simple: **Reduce repetitive manual work, save time, and make attendance processing easier.**

### How It Works

1. **Upload:** Teacher uploads a handwritten attendance sheet through the Streamlit interface.
2. **Text Extraction:** Tesseract OCR extracts roll numbers from the uploaded image.
3. **Verification:** Extracted roll numbers are displayed for review and correction.
4. **Automation:** Selenium automatically logs into the VM Edulife ERP portal.
5. **Attendance Marking:** Navigates to the attendance section and marks the corresponding students absent.
6. **Submission:** Submits the attendance records and displays the execution status.

### Key Features

- Extracts roll numbers from handwritten attendance sheets using OCR.
- Reduces repetitive manual attendance entry.
- Automates ERP login, navigation, and attendance submission.
- Provides a simple Streamlit interface for non-technical users.
- Connects handwritten records with digital attendance workflows.

### Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core application logic |
| Tesseract OCR | Handwritten text extraction |
| Selenium | Browser and ERP automation |
| Streamlit | Interactive user interface |
| ChromeDriver | Chrome browser automation |

### Real-World Impact

Instead of manually reading handwritten sheets and entering each absent student's roll number into the ERP portal, teachers can use one interface to process attendance.

This project demonstrates how **AI-assisted text extraction and automation can solve everyday administrative challenges in educational institutions.**

### Future Improvements

- Improve OCR accuracy for different handwriting styles.
- Support multiple attendance sheets.
- Add attendance history and execution reports.
- Extend compatibility with other ERP platforms.

### Developer

**Shridhar Kiran Patil**

B.Tech | Artificial Intelligence & Data Science

[GitHub](https://github.com/shridhar9700) | [Project Repository](https://github.com/shridhar9700/Attendance-Automation)

---

*Built to solve a practical problem, not just to build another application.*
