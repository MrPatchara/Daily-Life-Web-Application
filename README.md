# 🌟 Daily Life Web Application

<div align="center">

![Web Application](https://img.shields.io/badge/Web-Application-blue?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A collection of practical web tools for everyday life**

[Live Demo](https://mrpatchara.github.io/web-application-for-dailylife/index.html) • [Features](#-features) • [Usage](#-usage) • [License](#-license)

</div>

---

## 📖 About

Daily Life Web Application is a comprehensive multi-tool web application designed to help you with various everyday tasks. From health tracking to financial management, number conversion, and academic calculations, this application provides a suite of useful tools in one convenient place.

## ✨ Features

### 🏥 1. BMI Calculator (Health Record)
Calculate your Body Mass Index (BMI) with detailed health information tracking.

- **Personal Information**: Name, age, gender
- **Health Metrics**: Weight and height input
- **Activity Level**: Exercise frequency tracking
- **BMI Calculation**: Instant BMI calculation with categorization

### 💰 2. Income & Expense Tracker
Manage your finances with a comprehensive income and expense tracking system.

- **Transaction Recording**: Date-based income and expense entries
- **Visual Analytics**: Interactive charts using Chart.js
- **Data Export**: Export your financial data to Excel format
- **Balance Calculation**: Automatic balance tracking and reporting
- **Data Table**: Complete transaction history with totals

### 🔢 3. Base Number Converter
Convert numbers between different number bases (binary to hexadecimal and more).

- **Multiple Bases**: Support for bases 2, 3, 5, 8, 10, 12, and 16
- **Bidirectional Conversion**: Convert from any base to any base
- **Conversion History**: Track your recent conversions
- **Dark Mode**: Toggle between light and dark themes
- **Copy to Clipboard**: Easy result copying functionality

### 📊 4. Grade Calculator & Statistics
Calculate student grades and generate comprehensive statistics.

- **Grade Calculation**: Automatic grade assignment based on scores
- **Student Management**: Track multiple students with IDs and names
- **Statistical Analysis**: 
  - Average grade calculation
  - Minimum and maximum scores
  - Standard deviation
- **Search Functionality**: Find students by ID
- **Data Persistence**: History tracking with clear functionality

## 🚀 Getting Started

### Prerequisites

No installation required! This is a pure client-side web application that runs entirely in your browser.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/MrPatchara/web-application-for-dailylife.git
```

2. Navigate to the project directory:
```bash
cd web-application-for-dailylife
```

3. Open `index.html` in your web browser:
   - Simply double-click the `index.html` file, or
   - Use a local web server (recommended for development)

### Using a Local Web Server (Optional)

For the best experience, especially when testing features like Excel export, you may want to use a local web server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (http-server):**
```bash
npx http-server
```

Then open `http://localhost:8000` in your browser.

## 📱 Usage

### Accessing the Application

1. Open `index.html` in your web browser
2. You'll see the main menu with four available tools
3. Click on any tool to navigate to its dedicated page

### Using Each Tool

#### BMI Calculator
1. Enter your personal information (name, age, gender)
2. Input your weight (kg) and height (cm)
3. Select your exercise frequency
4. Click "Calculate BMI" to see your results

#### Income & Expense Tracker
1. Enter the date for your transaction
2. Input your income amount
3. Input your expense amount
4. Click "Add Record" to save the entry
5. View your data in the table and chart
6. Export to Excel when needed

#### Base Number Converter
1. Enter the number you want to convert
2. Select the source base (from)
3. Select the target base (to)
4. Click "Convert" to see the result
5. Use "Copy Result" to copy the converted number

#### Grade Calculator
1. Enter student ID, name, and surname
2. Input the score (0-100)
3. Click "Calculate" to see the grade
4. View statistics for all entered students
5. Use the search function to find specific students

## 🛠️ Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling and responsive design
- **JavaScript**: Interactive functionality and calculations
- **Chart.js**: Data visualization for income/expense tracking
- **SheetJS (xlsx)**: Excel file generation

## 📁 Project Structure

```
web-application-for-dailylife/
│
├── index.html              # Main landing page
├── mainstyles.css          # Main page styles
├── mainscripts.js          # Main page scripts
│
├── 1-health-record.html    # BMI Calculator page
├── styles.css              # BMI Calculator styles
├── script.js               # BMI Calculator logic
│
├── 2-money-income.html     # Income/Expense Tracker page
├── styles2.css            # Income/Expense Tracker styles
├── script2.js              # Income/Expense Tracker logic
│
├── 3-base-num-converter.html  # Number Converter page
├── styles3.css             # Number Converter styles
├── script3.js              # Number Converter logic
│
├── 4-garde-calculator.html # Grade Calculator page
├── styles4.css             # Grade Calculator styles
├── script4.js              # Grade Calculator logic
│
├── README.md               # Project documentation
└── LICENSE                 # MIT License
```

## 🎨 Features Highlights

- ✨ **Clean and Modern UI**: Beautiful, user-friendly interface
- 📱 **Responsive Design**: Works on desktop, tablet, and mobile devices
- 🎯 **No Dependencies**: Pure vanilla JavaScript (except Chart.js and xlsx for specific features)
- 💾 **Local Storage**: Data persistence in browser (where applicable)
- 🌙 **Dark Mode**: Available in the number converter tool
- 📊 **Data Visualization**: Charts and graphs for better data understanding
- 📥 **Export Functionality**: Export data to Excel format

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to this project:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Patchara Al-umaree**

- GitHub: [@MrPatchara](https://github.com/MrPatchara)
- Email: Patcharaalumaree@gmail.com

## 🙏 Acknowledgments

- Thanks to all contributors and users of this project
- Built with ❤️ for everyday convenience

## 📞 Contact & Support

If you have any questions, suggestions, or issues:

- 📧 Email: Patcharaalumaree@gmail.com
- 🐛 Issues: [GitHub Issues](https://github.com/MrPatchara/web-application-for-dailylife/issues)
- 🌐 Live Demo: [Visit the Website](https://mrpatchara.github.io/web-application-for-dailylife/index.html)

---

<div align="center">

**Made with ❤️ by Patchara Al-umaree**

⭐ Star this repo if you find it helpful!

</div>
