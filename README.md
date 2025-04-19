# 🔐 Password Generator Using JavaScript

🚀 **Live Demo:** [View on Vercel](https://password-generator-using-java-script.vercel.app)  
[![Vercel Deployment](https://img.shields.io/badge/vercel-deployed-%23000?logo=vercel)](https://password-generator-using-java-script.vercel.app)  

A secure, customizable password generator that creates strong passwords with visual strength indicators.

## ✨ Key Features

- 🔒 Generate passwords (8-32 characters)
- ⚙️ Customize character types (uppercase, lowercase, numbers, symbols)
- 📋 One-click copy to clipboard
- 📊 Visual strength meter
- 📱 Fully responsive design
- 🎨 Clean, modern interface

## 🛠️ Technologies

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/SukantaDatta18/Password-Generator-Using-JavaScript.git
Navigate to project directory:

bash
cd Password-Generator-Using-JavaScript
Open in your browser:

bash
open index.html  # Or double-click the file
🎨 Customization Guide
Changing Password Length
Edit in script.js:

javascript
const minLength = 8;   // Minimum password length
const maxLength = 32;  // Maximum password length
Modifying Character Sets
Update in script.js:

javascript
const uppercase = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
const lowercase = "abcdefghijklmnopqrstuvwxyz";
const numbers = "0123456789";
const symbols = "!@#$%^&*()_+~`|}{[]:;?><,./-=";
Adjusting Strength Meter
Modify the thresholds:

javascript
// Strength levels (0-100)
const strengthLevels = {
  weak: 30,
  medium: 60,
  strong: 80
};
🏗️ Project Structure
Password-Generator/
├── index.html          # Main HTML file
├── style.css           # All styling
├── script.js           # Password generation logic
└── assets/             # (Optional)
    ├── images/         # Screenshots/logo
    └── fonts/          # Custom fonts
🔧 How It Works
User selects password length (slider)

Chooses character types (checkboxes)

Clicks "Generate" button

System creates password based on selections

Strength meter updates visually

One-click copy available

📱 Responsive Design
Perfectly works on:

Mobile phones

Tablets

Desktop computers

📜 License
MIT License - see LICENSE file for details

<div align="center"> <p>Created with 💙 by <a href="https://github.com/SukantaDatta18">Sukanta Datta</a></p> <p>⭐ Star this repository if you find it useful!</p> </div> ```
