# 🌤️ Weather App — My First Python Project

Welcome to my very first Python project — a simple **Weather App** built with `PyQt5`, `requests`, and `python-dotenv`.  
This is also my **first GitHub repository**, created as a learning journey to explore the Python ecosystem and software development practices.

---

## 🚀 About the Project

This is a desktop GUI application that allows users to enter a city name and fetch current weather information using the **OpenWeatherMap API**. It displays:

- 🌡️ Temperature (in Fahrenheit)
- 🌦️ Weather condition emoji
- 📄 Description (like "clear sky", "light rain", etc.)

The goal is to learn and apply:
- Python programming basics
- GUI programming with PyQt5
- Using APIs
- Keeping secrets secure using `.env` and `python-dotenv`
- Git and GitHub workflows

---

## 📦 Technologies Used

- [Python 3.13](https://www.python.org/)
- [PyQt5](https://pypi.org/project/PyQt5/) — for the graphical interface
- [Requests](https://pypi.org/project/requests/) — for API calls
- [python-dotenv](https://pypi.org/project/python-dotenv/) — to handle API keys securely

---

## 🛠️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

## 🔐 API Key Setup

This project uses an API key that **should not** be hardcoded in the code for security reasons.  
To run the project locally, follow these steps:

### 1. Create a `.env` file
In the root directory of the project, create a file named `.env` and add your API key:

```
API_KEY="your_api_key_here"
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
````

Make sure `python-dotenv` is included in your `requirements.txt`.

### 3. Load the `.env` in your Python script

```python
from dotenv import load_dotenv
import os

load_dotenv()
api_key = os.getenv("MY_API_KEY")
```

---

## 🛠️ How to Run

```bash
python main.py
```

Replace `main.py` with the entry point of your project.

---

## 🔒 Security Notes

* ✅ `.env` is added to `.gitignore` so your API key is **never** pushed to GitHub.
* ✅ A `.env.example` file is included to show what variables are needed (without real values).
* 🚫 Never commit sensitive info like API keys or tokens!

---

## 📂 File Structure (Example)

```
my-project/
│
├── main.py
├── .env               # Your real API key (not committed)
├── .env.example       # Template for others to know what env variables to use
├── .gitignore
├── requirements.txt
└── README.md
```


---

## 📚 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Thanks to all the open-source contributors and docs that helped me learn this stuff!

