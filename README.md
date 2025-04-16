# 🚀 Streamlit App

A simple and interactive web application built with [Streamlit](https://streamlit.io/). This app leverages Python's power and an intuitive UI for data exploration, ML models, or anything you imagine.

## 📁 Project Structure

```
.
├── SLN/                    # Python virtual environment
├── app.py                  # Main Streamlit application
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

### 2. Create and Activate a Virtual Environment

```bash
python3 -m venv SLN
source SLN/bin/activate
```

### 3. Install Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
pip install matplotlib
pip install google-generativeai
pip install streamlit
```

---

## ▶️ Running the App

Make sure your virtual environment is activated:

```bash
source SLN/bin/activate
```

Then run the app:

```bash
streamlit run main.py
```

Your browser should automatically open at `http://localhost:8501`.

---

## 📦 Requirements

List of core packages used in the project:

```text
streamlit
google-generativeai
```

> Add other dependencies to `requirements.txt` as needed using `pip freeze > requirements.txt`.

---

## 📌 Notes

- Ensure you have Python 3.8 or later installed.
- If deploying, make sure to configure a `.streamlit/config.toml` file for customization (port, theme, etc.).

---


## 👨‍💻 Author

**Lakshminarayana Senagavarapu**  
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/lakshminarayana-senagavarapu/)!

