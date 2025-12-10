# TaskMaster-Web-App

**A Full-Stack Task Management Web Application**

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-Active-brightgreen.svg)

## 📋 Overview

TaskMaster is a modern, responsive task management web application designed to help users organize, prioritize, and track their daily tasks efficiently. Built with vanilla JavaScript, HTML5, and CSS3 on the frontend, and Node.js with Express on the backend, this application provides a seamless user experience with real-time updates and persistent data storage.

## ✨ Key Features

- ✅ **Task Management**: Create, read, update, and delete tasks with ease
- 📅 **Due Date Tracking**: Set and manage task deadlines
- 🎯 **Priority Levels**: Categorize tasks by priority (High, Medium, Low)
- 👤 **User Authentication**: Secure user registration and login system
- 🔄 **Real-Time Updates**: Instant synchronization across multiple sessions
- 📱 **Responsive Design**: Fully mobile-responsive interface
- 💾 **Data Persistence**: Tasks saved securely in database
- 🎨 **Modern UI**: Clean and intuitive user interface
- 🔒 **Secure**: Password hashing and session management

## 🛠️ Technology Stack

### Frontend
- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling and animations
- **JavaScript (ES6+)** - Interactive frontend logic
- **Fetch API** - Asynchronous HTTP requests

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **JWT** - JSON Web Tokens for authentication
- **bcryptjs** - Password hashing

### Tools & Platforms
- **Git** - Version control
- **npm** - Package management
- **Postman** - API testing

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)
- MongoDB (local or Atlas cluster)
- Git

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/pateljiop/TaskMaster-Web-App.git
cd TaskMaster-Web-App
```

2. **Install dependencies**
```bash
npm install
```

3. **Configure environment variables**
Create a `.env` file in the root directory:
```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
NODE_ENV=development
```

4. **Start the application**
```bash
npm start
```

5. **Access the application**
Open your browser and navigate to `http://localhost:5000`

## 📝 Usage

### Creating a Task
1. Click the "Add Task" button
2. Enter task title and description
3. Set priority level and due date
4. Click "Create Task"

### Editing a Task
1. Click the edit icon on any task
2. Modify the task details
3. Click "Save Changes"

### Deleting a Task
1. Click the delete icon on the task
2. Confirm the deletion

### Filtering Tasks
- Filter by priority level
- Filter by completion status
- Search by task title

## 📁 Project Structure

```
TaskMaster-Web-App/
├── public/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── app.js
│   └── index.html
├── src/
│   ├── models/
│   │   └── Task.js
│   ├── routes/
│   │   └── tasks.js
│   ├── middleware/
│   │   └── auth.js
│   └── server.js
├── .env
├── .gitignore
├── package.json
└── README.md
```

## 🔌 API Endpoints

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - Login user
- `POST /api/auth/logout` - Logout user

### Tasks
- `GET /api/tasks` - Retrieve all tasks
- `GET /api/tasks/:id` - Retrieve specific task
- `POST /api/tasks` - Create new task
- `PUT /api/tasks/:id` - Update task
- `DELETE /api/tasks/:id` - Delete task

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Hariom** - BCA Student & Aspiring Developer
- GitHub: [@pateljiop](https://github.com/pateljiop)
- Email: ahuzahariom@gmail.com
- Location: Ballia, Uttar Pradesh, India

## 🙏 Acknowledgments

- Thanks to all open-source contributors
- Inspired by modern task management applications
- Built as a learning project to master full-stack development

## 📞 Support

If you have questions or issues, please:
1. Check the existing [Issues](https://github.com/pateljiop/TaskMaster-Web-App/issues)
2. Create a new issue with detailed description
3. Contact via email: ahuzahariom@gmail.com

---

**Last Updated**: December 2024
**Status**: Actively Maintained ✅
