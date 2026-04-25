# ExpensePilot 💰

ExpensePilot is a modern, full-stack team budget tracker that helps users manage expenses, track income, and visualize financial data through interactive pie charts. Designed with a clean UI and smooth animations, it makes understanding your finances simple and intuitive.

✨ Features

💰 Add, edit, and delete expenses & income

🗂️ Categorize expenses (Travel, Food, Utilities, etc.)

💼 Track income sources (Freelance, Salary, etc.)

🥧 Interactive Pie Chart visualization

🖱️ Click on chart sections to see detailed insights

📊 Real-time financial summary

🌗 Dark / Light mode toggle

✨ Smooth animations with modern UI

📱 Fully responsive design


## Categories 📂

- Food 🍔
- Travel ✈️
- Accommodation 🏠
- Utilities ⚡
- Miscellaneous 📌
  


🧠 How It Works
Add your transactions (income or expenses)

Data is grouped by categories and sources

The pie chart shows distribution visually

Click on any section to see insights like:

“₹3000 spent on Travel”
“₹5000 earned from Freelancing”




🛠️ Tech Stack

Frontend:

HTML

Javascript

React (Vite fast building tool)

Styling: Tailwind CSS

Charts: Chart.js / Recharts

Backend: Node.js + Express / Firebase

Github

Database: MongoDB / Firestore

Recharts (visualizations)

Framer Motion (animations)

### Vercel (Frontend)
1. Push code to GitHub
2. Connect repository to Vercel
3. Set environment variables
4. Deploy

### Render (Backend)
1. Push code to GitHub
2. Create new Web Service on Render
3. Set environment variables
4. Deploy

## Browser Support 🌐

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
   
## Project Structure 📁

```
ExpensePilot/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── hooks/
│   │   ├── assets/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── server.js
│   └── package.json
├── README.md
├── .gitignore
└── .env.example
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

The app will run on `[http://localhost:5173]/(https://dheerajkr9.github.io/Expense_Pilott)`

### Backend Setup

```bash
cd backend
npm install
# Create .env file with MongoDB URI
npm start
```

The server will run on `http://localhost:5000`

### Environment Variables

Create a `.env` file in the backend folder:

```
MONGODB_URI=mongodb://localhost:27017/expensepilot
PORT=5000
NODE_ENV=development
```

Or use MongoDB Atlas:

```
MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/expensepilot
PORT=5000
NODE_ENV=development
```

## How to Use 📖

1. **Add Budget**: Set your total budget in the summary section
2. **Add Expense**: Fill the expense form with amount, description, category, date, and who paid
3. **View Charts**: See visual breakdown of spending by category
4. **Edit/Delete**: Manage expenses from the list
5. **Track Team**: See who spent what in the contribution section

## Features in Detail 🎯

### Dashboard
- Clean card-based layout
- Animated counter displays
- Real-time budget calculations
- Status indicators (on track, warning, over budget)

### Charts
- **Pie Chart**: Category-wise spending distribution
- **Bar Chart**: Monthly spending trends
- Smooth animated transitions

### Expense Management
- Add, edit, delete expenses
- Filter by category
- Search functionality
- Date range filtering

### Theme Support
- Light mode (default)
- Dark mode toggle
- Smooth theme transitions

🎯 Use Cases

👨‍🎓 Students managing monthly expenses

✈️ Trip budget tracking

👥 Team expense management

💡 Hackathon projects

🌟 Future Improvements

Expense splitting (like Splitwise)

Authentication system

Monthly analytics & reports

Export to PDF/Excel


💡 Inspiration

Inspired by modern fintech apps focused on simplicity, clarity, and user experience.


🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.


## License 📄

MIT License - feel free to use for personal or commercial projects

## Support & Feedback 💬

Found a bug? Have a suggestion? Feel free to open an issue or contribute!

---

**Made with ❤️ for better budget management (by Ayush Pandey,Dheeraj Kumar,Ayush Singh And Avinash Vishwakarma)**
