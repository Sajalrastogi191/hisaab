# 💰 Hisaab - Smart Expense Splitter

A modern, responsive web application for splitting expenses among friends, roommates, or group activities. Built with vanilla HTML, CSS, and JavaScript.

## ✨ Features

### 🎯 Core Functionality
- **Add People**: Easily add participants to your expense group
- **Track Expenses**: Record who paid for what and who benefited
- **Smart Settlement**: Automatically calculate the minimum number of transactions needed to settle all debts
- **Real-time Updates**: All calculations update instantly as you add expenses

### 🎨 Design & UX
- **Modern Interface**: Clean, professional design with smooth animations
- **Dark/Light Theme**: Toggle between themes with a single click
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Hover effects and smooth transitions throughout

### 📊 Analytics
- **Statistics Dashboard**: View total expenses, average spending, and participant count
- **Transaction History**: See all expenses with dates and details
- **Settlement Summary**: Clear visualization of who owes whom

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or installation required!

### Usage
1. **Download** the HTML file or copy the code
2. **Open** the file in your web browser
3. **Start** by adding people to your group
4. **Add expenses** by selecting who paid, the amount, and who benefited
5. **Calculate settlement** to see who owes money to whom

## 📱 How to Use

### Step 1: Add Participants
```
1. Enter a person's name in the "Add People" section
2. Click "Add Person" or press Enter
3. Repeat for all group members
```

### Step 2: Record Expenses
```
1. Select who paid from the dropdown
2. Enter the expense amount
3. Check boxes for who benefited from the expense
4. Click "Add Expense"
```

### Step 3: Settle Up
```
1. Click "Calculate Settlement"
2. View the optimized payment plan
3. Follow the instructions to settle all debts
```

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **Vanilla JavaScript**: No frameworks or dependencies
- **Local Storage**: All data stored in browser memory (session-based)

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 60+
- ✅ Safari 12+
- ✅ Edge 79+

### File Structure
```
hisaab-expense-splitter.html
├── HTML Structure
├── Embedded CSS Styles
└── JavaScript Logic
```

## 🎯 Algorithm

The expense settlement uses an optimized debt settlement algorithm:

1. **Calculate Balances**: Determine net balance for each person
2. **Separate Creditors/Debtors**: Split into those owed money vs. those who owe
3. **Sort by Amount**: Order from highest to lowest amounts
4. **Minimize Transactions**: Match creditors with debtors to reduce transaction count
5. **Generate Instructions**: Provide clear payment instructions

## 🌟 Key Features Explained

### Smart Debt Settlement
- Minimizes the number of transactions needed
- Handles complex multi-person scenarios
- Provides clear, actionable payment instructions

### Theme System
- **Light Theme**: Clean, bright interface for daytime use
- **Dark Theme**: Easy on the eyes for low-light environments
- **Smooth Transitions**: Seamless switching between themes

### Responsive Design
- **Mobile-First**: Optimized for touch interfaces
- **Adaptive Layouts**: Adjusts to any screen size
- **Touch-Friendly**: Large tap targets and intuitive gestures

## 💡 Use Cases

### Perfect For:
- 🏠 **Roommate Expenses**: Rent, utilities, groceries
- 🍕 **Group Dining**: Restaurant bills, food delivery
- ✈️ **Travel Groups**: Hotels, transportation, activities
- 🎉 **Events**: Party planning, group gifts
- 👥 **Office Teams**: Lunch orders, team events

## 🔒 Privacy & Security

- **No Data Collection**: Your data never leaves your browser
- **Session-Based**: Data is cleared when you close the browser
- **No Registration**: No accounts or personal information required
- **Offline Capable**: Works without internet connection

## 🎨 Customization

### Themes
The app includes built-in light and dark themes. You can customize colors by modifying the CSS custom properties:

```css
:root {
    --primary-color: #6366f1;    /* Main brand color */
    --secondary-color: #10b981;  /* Accent color */
    --bg-primary: #ffffff;       /* Background color */
    /* ... more variables */
}
```

### Features
The modular JavaScript structure makes it easy to add new features:
- Currency support
- Export functionality
- Expense categories
- Photo attachments

## 🐛 Troubleshooting

### Common Issues

**Q: My expenses aren't showing up**
A: Make sure you've added people first, then selected both a payer and beneficiaries

**Q: Settlement calculations seem wrong**
A: The algorithm optimizes for minimum transactions - manual calculations might differ

**Q: Theme toggle not working**
A: Ensure JavaScript is enabled in your browser

**Q: Mobile layout looks broken**
A: Try refreshing the page or using a different browser

## 🤝 Contributing

This is a single-file application perfect for:
- Educational purposes
- Learning expense splitting algorithms
- Customization and enhancement
- Integration into larger projects

### Enhancement Ideas
- [ ] Multiple currency support
- [ ] Export to CSV/PDF
- [ ] Expense categories
- [ ] Photo receipts
- [ ] Group templates
- [ ] Payment tracking
- [ ] Email notifications

## 📄 License

This project is open source and available under the MIT License. Feel free to use, modify, and distribute as needed.

## 🙏 Acknowledgments

- Built with modern web standards
- Inspired by popular expense splitting apps
- Designed for simplicity and efficiency

## 📞 Support

For issues, questions, or feature requests:
1. Check the troubleshooting section above
2. Review the code comments for technical details
3. Test in a different browser if problems persist

---

**Made with ❤️ for hassle-free expense splitting**

*Hisaab (हिसाब) means "account" or "calculation" in Hindi - keeping track of shared expenses made simple.*
 
 
