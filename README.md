# 🩺 TechCare — Patient Health Dashboard

A web-based healthcare dashboard that displays patient information, health measurements, diagnostic results, and laboratory reports in one place.

## 🌟 About the Project

The TechCare Patient Dashboard was developed as a frontend web development project based on a provided Adobe XD design. It uses patient data from an API to display Jessica Taylor’s profile and medical information in an organized and user-friendly interface.

The project helped me practice webpage design, API integration, JavaScript, and data visualization.

## 🚀 Key Features

- 👤 **Patient Profile:** Displays Jessica Taylor’s personal and contact information.
- 💓 **Health Measurements:** Shows blood pressure, temperature, and heart rate.
- 📊 **Blood Pressure Chart:** Visualizes blood pressure history using Chart.js.
- 🩺 **Diagnostic Information:** Displays available diagnostic results.
- 🧪 **Lab Results:** Shows laboratory reports and related information.
- 🔗 **API Integration:** Retrieves patient data dynamically.
- 🎨 **Clean Interface:** Follows the provided design reference.

## 💻 Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the webpage |
| CSS3 | Styling and layout |
| JavaScript | Application logic and data handling |
| Fetch API | Retrieving patient information |
| Chart.js | Displaying the blood pressure chart |

## 📂 Project Structure

```text
techcare-patient-dashboard/
│
├── index.html
├── style.css
├── script.js
├── README.md
│
└── asserts/
    ├── images
    └── icons
```
### Run the Project

1. Download or clone the project repository.
2. Open the project folder in Visual Studio Code.
3. Open the terminal.
4. Run this command:

   ```bash
   python -m http.server 8000
   ```

5. Open your browser and visit:

   `http://localhost:8000`

## 🔌 API Details

The application retrieves patient information from the provided Coalition Technologies API.

- **Request method:** GET
- **Authentication:** Basic Authentication
- **API endpoint:** https://fedskillstest.coalitiontechnologies.workers.dev

The retrieved data is used to populate the patient profile, health measurements, diagnostic information, lab results, and blood pressure chart.

## 🎨 Design Reference

The project was created with reference to the supplied Adobe XD design.

🔗 [View the Adobe XD design](https://xd.adobe.com/view/3f9ab587-7536-4db8-a7dd-64d474e10867-6ac9/?hints=off)

## 👩‍💻 Project Information

**Project:** TechCare Patient Health Dashboard  
**Type:** Frontend Web Development  
**Tools:** Visual Studio Code and Git

---

💙 *Built as a learning project to improve my frontend development skills.*
