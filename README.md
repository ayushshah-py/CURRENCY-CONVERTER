# 💱 Currency Converter using Python Tkinter

A simple yet powerful desktop GUI application built with **Python** and **Tkinter** that allows users to convert currencies in real time. This tool fetches live exchange rates and performs accurate conversions between a wide range of currencies.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🖥️ Screenshots

Here is the main interface of the Currency Converter app:

![Currency Converter GUI](https://github.com/ayushshah-py/CURRENCY-CONVERTER/blob/main/CURRENCY%20CONVERTER%20.png?raw=true)


## 📌 Table of Contents

* [📌 Table of Contents](#-table-of-contents)
* [✨ Features](#-features)
* [🖥️ Screenshots](#️-screenshots)
* [📂 Project Structure](#-project-structure)
* [⚙️ Requirements](#️-requirements)
* [🚀 Installation and Setup](#-installation-and-setup)
* [🔧 How It Works](#-how-it-works)
* [🔒 Security](#-security)
* [📈 Future Enhancements](#-future-enhancements)
* [🧑‍💻 Author](#-author)
* [📜 License](#-license)

--------------------------------------------------------------------------------------

## ✨ Features

* ✅ Graphical User Interface with **Tkinter**
* ✅ Converts currency values between multiple international currencies
* ✅ Fetches **real-time exchange rates** (if connected to an API)
* ✅ Easy-to-use and intuitive layout
* ✅ Built-in validation for numeric inputs
* ✅ Lightweight and fast performance
* ✅ Responsive and error-handled GUI experience

----------------------------------------------------------------------------------------
## 📂 Project Structure

```
currency_converter/
│
├── main.py                # Main Python script with GUI and logic
├── README.md              # Project documentation
├── requirements.txt       # List of dependencies
└── assets/                # Optional: icons, images, or logos
```

---

## ⚙️ Requirements

Before running the application, ensure you have the following Python modules installed:

* `tkinter` (usually comes with Python)
* `requests` *(optional: for live currency API access)*

Install the requirements using:

```bash
pip install -r requirements.txt
```

If you don’t have a `requirements.txt`, manually install using:

```bash
pip install requests
```

---

## 🚀 Installation and Setup

1. **Clone the Repository:**

```bash
git clone https://github.com/ayushshah-py/CURRENCY-CONVERTER.git
cd CURRENCY-CONVERTER
```

2. **Run the Application:**

```bash
python main.py
```

3. The Currency Converter GUI will launch.

---

## 🔧 How It Works

1. **User Input**: Enter the amount to convert and select source and target currencies.
2. * If using **static rates**: it applies pre-defined conversion values.
3. **Output**: The result is displayed in the output field.
4. **Error Handling**: Invalid inputs or missing selections are handled gracefully with user-friendly alerts.

## 🔒 Security

* API keys (if used) are not exposed in the GUI.
* Input fields are sanitized and validated.
* No personal user data is collected.

---

## 📈 Future Enhancements

* 🌐 Add dropdown auto-search for currencies
* 💾 Store user conversion history
* 📊 Graphical representation of currency trends
* 🌓 Dark/Light mode toggle
* 📱 Convert to a mobile app using **Kivy** or **Flutter**

---

## 🧑‍💻 Author

**AYUSH SHAH**

💼 Passionate Python Developer
📫 Reach me at: ayushs1904@gmail.com
🌐 GitHub: [https://github.com/ayushshah-py](https://github.com/ayushshah-py)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

Let me know if you want to:

* Add screenshots
* Include your actual API
* Convert it to a `.docx` or PDF
* Add dark mode, graphing, or another feature to your code

Just drop the code and I’ll help enhance it too!
