# 📊 IITM TDS Project 1

> Web application built with FastAPI for the Tools in Data Science (TDS) course at IIT Madras

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📋 Overview

This project is part of the **Tools in Data Science (TDS)** course at IIT Madras. It demonstrates building a modern web application using FastAPI, a high-performance Python web framework.

---

## ✨ Features

- **FastAPI Framework**: Modern, fast web framework for building APIs
- **Async Support**: Asynchronous request handling for better performance
- **Auto Documentation**: Automatic interactive API documentation (Swagger UI)
- **Type Safety**: Python type hints for better code quality
- **Easy Deployment**: Ready for deployment with Uvicorn server

---

## 🚀 Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/zetroretron/IITM_TDS_1.git
   cd IITM_TDS_1
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   
   # On Windows
   venv\\Scripts\\activate
   
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

## 💻 Usage

### Running the Application

Start the development server:

```bash
uvicorn app.main:app --reload
```

The application will be available at:
- **API**: http://localhost:8000
- **Interactive Docs**: http://localhost:8000/docs
- **Alternative Docs**: http://localhost:8000/redoc

### Running in Production

```bash
uvicorn app.main:app --host 0.0.0.0 --port 8000
```

---

## 📁 Project Structure

```
IITM_TDS_1/
├── app/                    # Application code
│   └── main.py            # FastAPI application entry point
├── .gitignore             # Git ignore rules
├── LICENSE                # MIT License
├── README.md              # This file
├── env.txt                # Environment variables template
├── requirements.txt       # Python dependencies
├── runtime.txt            # Python runtime version
└── test_github.py         # Test file
```

---

## 🔧 Configuration

### Environment Variables

Create a `.env` file based on `env.txt`:

```env
# Add your environment variables here
API_KEY=your_api_key_here
DEBUG=True
```

---

## 📚 API Documentation

Once the server is running, visit:

- **Swagger UI**: http://localhost:8000/docs
  - Interactive API documentation
  - Test endpoints directly from the browser
  
- **ReDoc**: http://localhost:8000/redoc
  - Alternative documentation format
  - Clean, readable API reference

---

## 🧪 Testing

Run tests using:

```bash
python test_github.py
```

---

## 🚢 Deployment

### Deploy to Heroku

1. Install Heroku CLI
2. Login to Heroku:
   ```bash
   heroku login
   ```

3. Create a new app:
   ```bash
   heroku create your-app-name
   ```

4. Deploy:
   ```bash
   git push heroku main
   ```

### Deploy to Railway

1. Go to [Railway.app](https://railway.app/)
2. Connect your GitHub repository
3. Railway will auto-detect FastAPI and deploy

### Deploy to Render

1. Go to [Render.com](https://render.com/)
2. Create a new Web Service
3. Connect your repository
4. Set start command: `uvicorn app.main:app --host 0.0.0.0 --port $PORT`

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **FastAPI** | Web framework |
| **Uvicorn** | ASGI server |
| **Python 3.8+** | Programming language |
| **Pydantic** | Data validation |

---

## 📖 Learn More

- [FastAPI Documentation](https://fastapi.tiangolo.com/)
- [Uvicorn Documentation](https://www.uvicorn.org/)
- [Python Type Hints](https://docs.python.org/3/library/typing.html)

---

## 🤝 Contributing

This is an academic project, but suggestions and improvements are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Course:** Tools in Data Science (TDS)  
**Institution:** IIT Madras  
**Student ID:** 23f2004645

---

## 🎯 Learning Objectives

This project demonstrates:
- Building RESTful APIs with FastAPI
- Asynchronous programming in Python
- API documentation best practices
- Modern Python development workflows
- Deployment strategies for web applications

---

**Built with 🐍 Python & ⚡ FastAPI | IIT Madras TDS Course**
