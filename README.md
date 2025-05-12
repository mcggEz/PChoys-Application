# 🐱 Purrfect Choys

A mobile-first report management system designed to streamline daily operations for store owners.

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 📱 Overview

Purrfect Choys is a comprehensive report management system tailored for store owners who need an efficient way to track and manage daily reports. This mobile-first application simplifies the reporting process while providing powerful insights through an intuitive dashboard.

### ✨ Key Features

- **📊 Daily Reporting System**
  - Seamless report creation and submission
  - Real-time updates
  - Customizable report templates

- **📈 Owner Dashboard**
  - Comprehensive summary views
  - Performance metrics and trends
  - Export capabilities

- **🔐 Secure Authentication**
  - Role-based access control
  - Encrypted data transmission
  - Secure login system

- **👥 User Management**
  - Staff account creation
  - Role assignment
  - Activity tracking

## 🛠️ Tech Stack

### Frontend
- **React Native** - Mobile application framework
- **NativeWind** - Tailwind CSS for React Native
- **React Navigation** - Navigation library
- **Axios** - HTTP client

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **JWT** - Authentication
- **Mongoose** - MongoDB object modeling

## 📦 Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/purrfect-choys.git
cd purrfect-choys
```

2. Install dependencies
```bash
# Install frontend dependencies
cd mobile
npm install

# Install backend dependencies
cd ../backend
npm install
```

3. Set up environment variables
```bash
# In backend directory
cp .env.example .env
# Edit .env with your configuration
```

4. Start the development servers
```bash
# Start backend server
cd backend
npm run dev

# Start mobile app
cd mobile
npm start
```

## 📱 Mobile App Setup

1. Install Expo Go on your mobile device
2. Scan the QR code from the terminal after running `npm start`
3. The app will load on your device

## 🔧 Configuration

The application requires the following environment variables:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
API_PORT=3000
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter)

Project Link: [https://github.com/yourusername/purrfect-choys](https://github.com/yourusername/purrfect-choys)

---

Made with ❤️ and ☕
