# Personal Finance Manager 💰

A comprehensive personal finance management application built with the MERN stack (MongoDB, Express.js, React, Node.js). Track expenses, manage budgets, set financial goals, and generate detailed reports with an intuitive and responsive interface.

## 🚀 Features

### 💳 Expense Tracking
- Record income and expenses with detailed categorization
- Filter transactions by date, category, amount, and type
- Visual charts and analytics for spending patterns
- Recurring expense management for subscriptions and bills

### 📊 Budget Management
- Create monthly and yearly budgets by category
- Real-time budget monitoring with usage tracking
- Automated alerts when approaching spending limits
- Budget variance analysis and recommendations

### 🎯 Financial Goals
- Set savings, investment, and purchase goals with deadlines
- Visual progress tracking with achievement notifications
- Goal feasibility analysis and recommendations
- Multiple goal categories (savings, investment, debt, emergency)

### 📈 Financial Planning & Forecasting
- Advanced trend analysis for income and expenses
- 6-36 month financial projections
- AI-powered recommendations for financial improvement
- Goal achievement timeline predictions

### 📋 Comprehensive Reports
- Detailed expense reports with interactive charts
- Income tracking and source analysis
- Budget performance reports with variance analysis
- Export data in CSV and PDF formats

### 🔔 Smart Notifications
- Real-time alerts for budget limits and goal deadlines
- Recurring expense due date reminders
- Customizable notification preferences
- Priority-based notification system

### 👤 User Management
- Secure authentication with JWT tokens
- Multi-factor authentication (MFA) support
- Comprehensive user profile management
- Financial preferences and settings

### 🔒 Security Features
- Password hashing with bcrypt
- QR code-based MFA setup
- Input validation and sanitization
- Secure API endpoints with authentication

## 🛠️ Tech Stack

### Frontend
- **React 18** - Modern UI library with hooks
- **Vite** - Fast build tool and development server
- **TailwindCSS** - Utility-first CSS framework
- **Redux Toolkit** - State management
- **React Query** - Data fetching and caching
- **Chart.js** - Interactive data visualizations
- **Formik & Yup** - Form handling and validation
- **React Router** - Client-side routing
- **Framer Motion** - Smooth animations

### Backend Dependencies
- **Node.js & Express.js** - Server runtime and framework
- **MongoDB & Mongoose** - Database and ODM
- **JWT** - Authentication tokens
- **bcryptjs** - Password hashing
- **Speakeasy** - MFA implementation
- **Chart.js & Recharts** - Data visualization
- **json2csv & pdfmake** - Data export functionality

## 📦 Installation

### Prerequisites
- Node.js (v16 or higher)
- MongoDB (local installation or cloud service)
- Git

### 1. Clone the Repository
```bash
git clone <repository-url>
cd frontend
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Environment Setup
Create a `.env` file in the backend directory:
```env
MONGO_URI=mongodb://localhost:27017/personal-finance-manager
JWT_SECRET=your-super-secret-jwt-key-here
PORT=8000
NODE_ENV=development
```

### 4. Start Development Server
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## 🎮 Usage

### Getting Started
1. **Register/Login** - Create an account or sign in
2. **Setup Profile** - Configure your financial preferences
3. **Add Transactions** - Start recording your income and expenses
4. **Create Budgets** - Set spending limits for different categories
5. **Set Goals** - Define your financial objectives
6. **Monitor Progress** - Use the dashboard to track your financial health

### Key Workflows

#### Expense Tracking
1. Navigate to "Add Transaction"
2. Select transaction type (income/expense)
3. Choose or create a category
4. Enter amount, date, and description
5. View transactions in the dashboard with filtering options

#### Budget Management
1. Go to "Budgets" section
2. Click "Create Budget"
3. Set category, amount, and time period
4. Monitor usage in real-time
5. Receive alerts when approaching limits

#### Goal Setting
1. Access "Goals" dashboard
2. Create new goal with target amount and deadline
3. Select goal category (savings, investment, etc.)
4. Track progress and receive achievement notifications

#### Report Generation
1. Visit "Reports" section
2. Select report type (expense, income, budget, comprehensive)
3. Set date range and filters
4. View interactive charts and analytics
5. Export data as CSV or PDF

## 📱 Responsive Design

The application is fully responsive and optimized for:
- 📱 Mobile devices (320px+)
- 📱 Tablets (768px+)
- 💻 Desktop computers (1024px+)
- 🖥️ Large screens (1440px+)

## 🔧 Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build production-ready application
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality checks

## 📊 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Auth/           # Authentication components
│   ├── Budget/         # Budget management
│   ├── Goals/          # Financial goals
│   ├── Reports/        # Report generation
│   ├── Transactions/   # Expense tracking
│   ├── Users/          # User management
│   └── Layout/         # Layout components
├── services/           # API service functions
├── redux/              # State management
├── utils/              # Utility functions
└── assets/             # Static assets
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support

For support and questions:
- Check the [Setup Guide](SETUP_GUIDE.md) for detailed installation instructions
- Review the [Analysis Summary](ANALYSIS_SUMMARY.md) for technical details
- Open an issue for bug reports or feature requests

## 🙏 Acknowledgments

- Built with [Vite](https://vitejs.dev/) for fast development
- Styled with [TailwindCSS](https://tailwindcss.com/) for modern UI
- Charts powered by [Chart.js](https://www.chartjs.org/)
- Icons from [Heroicons](https://heroicons.com/) and [React Icons](https://react-icons.github.io/react-icons/)

---

**Made with ❤️ for better financial management**
