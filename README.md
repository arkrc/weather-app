# 🌦️ WeatherApp

A simple GUI-based Weather App built with **Python**, **PyQt5**, and the **OpenWeather API**.

This is my first Python project and my first GitHub repository. I'm using it as a learning experience to explore how APIs, GUIs, and packaging work together.

---

## ✨ Features

- Enter any city to get real-time weather
- Fetches data from [OpenWeather API](https://openweathermap.org/current)
- Displays temperature, weather condition, and emoji icon
- Built using PyQt5 for the UI
- Converts to `.exe` using PyInstaller

---

## 🚀 How to Run

### 🖥️ Option 1: Run from Python (for developers)
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/WeatherApp.git
   cd WeatherApp
    ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file:

   ```
   API_KEY=your_openweather_api_key_here
   ```

4. Run the app:

   ```bash
   python main.py
   ```

---

### 💡 Option 2: Run the `.exe` (for users)

1. Download the latest release ZIP from [GitHub Releases](../../releases)
2. Unzip the file
3. Open the `.env` file and add your API key:

   ```
   API_KEY=your_openweather_api_key_here
   ```
4. Double-click `WeatherApp.exe` to launch!

---

## 🗂 Project Structure

```
WeatherApp/
├── main.py
├── .env.example
├── requirements.txt
├── README.md
└── dist/
    ├── WeatherApp.exe
    └── .env
```

---

## 📦 Dependencies

* `requests`
* `python-dotenv`
* `PyQt5`

All are listed in `requirements.txt`.

---

## 🔐 Security Note

* The `.env` file is **never uploaded to GitHub**.
* Make sure to keep your API key **private** and **do not share** the `.env` file with others.

---

## 📜 License

MIT License — feel free to fork and modify.

---

## 🙌 Credits

Thanks to:

* [OpenWeather](https://openweathermap.org/) for the free API
* PyQt5 and the Python community for the great libraries

---

