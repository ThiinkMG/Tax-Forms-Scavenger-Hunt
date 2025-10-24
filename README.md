# Tax Forms Scavenger Hunt

An interactive educational tool designed to help students and families master tax form navigation and locate key information needed for FAFSA completion.

## 📋 Overview

This project is an interactive web application that teaches users how to navigate tax forms effectively through a scavenger hunt format. Users learn to locate critical information like Adjusted Gross Income (AGI), Federal Income Tax Paid, and other essential data points required for accurate FAFSA completion.

### Try it out

[Try Tax Form Scavenger Hunt (Online Link)](https://thiinkmg.github.io/Tax-Forms-Scavenger-Hunt/)

---

## ✨ Features

- **Interactive Scavenger Hunt**: 5 carefully crafted questions to test tax form knowledge
- **Visual Tax Form Examples**: Interactive Form 1040 with clickable sections and explanations
- **Real-time Progress Tracking**: Visual progress bar and statistics tracking
- **Comprehensive Visual Guide**: Detailed explanations of key tax form sections
- **Dark/Light Mode**: Toggle between themes for comfortable viewing
- **Auto-save Functionality**: Progress is automatically saved in browser storage
- **PDF Export**: Download results and visual guides as PDF files
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Tabbed Navigation**: Organized content across multiple sections

## 🎯 Educational Value

The scavenger hunt covers essential tax form navigation topics including:
- Locating Adjusted Gross Income (AGI) on Form 1040
- Finding Federal Income Tax Paid amounts
- Understanding W-2 form key boxes
- Identifying self-employment income on Schedule C
- Distinguishing between gross income and AGI
- Common mistakes to avoid when completing FAFSA

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software installation required

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start the scavenger hunt immediately!

### Usage
1. **Overview Tab**: Learn about key tax forms and what information you'll need to find
2. **Scavenger Hunt Tab**: Complete interactive questions to test your knowledge
3. **Tax Forms Tab**: Explore interactive Form 1040 with clickable sections
4. **Visual Guide Tab**: Access comprehensive explanations of tax form sections
5. **Export Results**: Download your progress and guides as PDF files

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript**: No frameworks required
- **jsPDF**: Client-side PDF generation
- **Local Storage**: Automatic progress saving

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📱 Responsive Design

The application is fully responsive and optimized for:
- **Desktop**: Full feature experience with hover effects
- **Tablet**: Touch-friendly interface with adapted layouts
- **Mobile**: Streamlined design for smaller screens

## 🎨 Customization

The application uses CSS custom properties (variables) for easy theming:
- Brand colors can be modified in the `:root` selector
- Dark mode colors are defined in the `.dark-mode` class
- All transitions and animations can be customized

## 📊 Scavenger Hunt Data Structure

The hunt questions are stored in a JavaScript array with the following structure:
```javascript
{
    id: number,
    question: string,
    description: string,
    options: string[],
    correct: number,
    explanation: string
}
```

## 🔧 Development

### Local Development
1. Clone the repository
2. Open `index.html` in your browser
3. Make changes to the code
4. Refresh the browser to see changes

### Adding New Questions
To add new scavenger hunt questions:
1. Add a new object to the `huntData` array in the JavaScript section
2. Follow the existing data structure format
3. The application will automatically include the new question

### Adding New Tax Form Sections
To add new interactive tax form sections:
1. Add new elements with the `interactive-highlight` class
2. Include a `data-info` attribute with the section identifier
3. Add the corresponding explanation to the `infoMap` object

## 📄 PDF Export Features

The application includes two PDF export options:
1. **Results PDF**: Complete scavenger hunt results with performance metrics
2. **Visual Guide PDF**: Comprehensive tax form navigation guide

## 🎓 Educational Use Cases

Perfect for:
- **High School Students**: Learning tax form basics before college
- **College Students**: Understanding tax forms for FAFSA completion
- **Parents**: Gaining knowledge to help their children
- **Financial Aid Counselors**: Educational tool for workshops and counseling
- **Community Organizations**: Financial literacy programs and workshops
- **Tax Preparers**: Training tool for FAFSA-related tax form questions

## 🏛️ Tax Forms Covered

- **Form 1040**: Main individual tax return with AGI and federal tax paid
- **W-2 Forms**: Wage and tax statements from employers
- **Schedule C**: Self-employment income and expenses
- **Common Mistakes**: W-2 vs. 1040 confusion, gross income vs. AGI

## 📅 Key Information Locations

- **Adjusted Gross Income (AGI)**: Line 11 on Form 1040
- **Federal Income Tax Paid**: Line 24 on Form 1040
- **Wages and Salaries**: Box 1 on W-2 forms
- **Self-Employment Income**: Line 31 on Schedule C

## 🔧 Advanced Features

### Interactive Tax Form
- Clickable sections with detailed explanations
- Visual highlighting of important areas
- Real-time feedback on form navigation

### Progress Tracking
- Visual progress bar with completion percentage
- Correct/incorrect answer tracking
- Automatic state persistence

### PDF Generation
- Professional PDF layout with MCF branding
- Detailed results with explanations
- Comprehensive visual guide export

## 🤝 Contributing

We welcome contributions to improve this educational tool:
1. Fork the repository
2. Create a feature branch
3. Make your improvements
4. Submit a pull request

## 📞 Support

For questions or support, please contact:
- [**My College Finance Technical Feedback Form**](https://docs.google.com/forms/d/e/1FAIpQLScyBwnqiz1L3ZOxV3C4f40jsOAW-YCw8xxfoBhPg2mgORshFA/viewform)

## 📜 License

© 2025 My College Finance. All rights reserved.

## 🙏 Acknowledgments

**Created by**: [Thiink Media Graphics](https://www.thiinkmediagraphics.com/)  
**In partnership with**: [My College Finance](https://www.mycollegefinance.com/)

## 🔗 Related Resources

- [FAFSA Interactive Research Web Report](https://my-college-finance.github.io/FAFSA-Interactive-Research-Web-Report/)
- [My College Finance Main Website](https://www.mycollegefinance.com/)
- [FAFSA Official Website](https://studentaid.gov/h/apply-for-aid/fafsa)
- [IRS Tax Forms and Instructions](https://www.irs.gov/forms-instructions)

---

*This educational tool is designed to help students and families navigate tax forms effectively for FAFSA completion. Always consult with tax professionals for personalized advice and verify information with official IRS resources.*
