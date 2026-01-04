

# Google Search Automations 🤖🔍

This repository contains Python scripts using **Selenium WebDriver (Microsoft Edge)** to automate Google and Bing searches in a **human-like manner**.  
It simulates typing behavior, scrolling, random delays, and link clicks.

> ⚠️ **Educational & Testing Purpose Only**  
> Do **NOT** use this project to manipulate search rankings, ads, or violate Google/Bing Terms of Service.

---

## 📁 Project Structure


Google-search-automations/
│
├── auto.py
├── from selenium import webdriver.py
├── from selenium import webdriver1.py
├── from selenium import webdriver2.py
├── from selenium import webdriver3.py
├── msedgedriver.exe
└── README.md

---

## 🧠 What Each File Does

### `auto.py`
✅ Main automation script  
- Performs Google searches
- Simulates **human typing**
- Scrolls pages randomly
- Clicks random search results
- Returns back to search results
- Uses **Edge WebDriver with Service**

### `from selenium import webdriver.py`
- Simple **Bing search automation**
- Demonstrates basic Selenium usage

### `from selenium import webdriver1.py`
- Demonstrates Edge WebDriver initialization with `Service`

### `from selenium import webdriver2.py`
- Shows Edge WebDriver with **custom Edge binary location**

### `from selenium import webdriver3.py`
- Runs Edge browser in **headless mode**

### `msedgedriver.exe`
- Microsoft Edge WebDriver (must match your Edge version)

---

## 🛠️ Requirements

- Python **3.8+**
- Microsoft Edge Browser
- Selenium

### Install Selenium
```bash
pip install selenium
```
### ⚙️ Setup Instructions
**1.Clone the repository**
```bash
git clone https://github.com/BS-World/Google-search-automations.git
cd Google-search-automations
```

**Check Edge Version**

**Open edge://settings/help**

**Download matching EdgeDriver from:**
https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
Update Driver Path in ```auto.py```
```bash
driver_path = r"D:\path\to\msedgedriver.exe"
```

▶️ How to Run
python ```auto.py```

🔎 Example Search Configuration
search_texts = [
  "internspark.in",
  "Internspark Internship internspark.in",
  "Internspark Online Internship Platform internspark.in"
]

repeat_count = 10

⚠️ Important Warnings

🚫 Do NOT use for:

SEO manipulation

Fake traffic

Ad clicking

Ranking abuse

✅ Allowed usage:

Selenium learning

Automation testing

Browser behavior simulation

Educational demos

📌 Best Practices

Use low repeat counts

Add random delays

Avoid running continuously

Prefer headless mode for testing

📄 License

This project is licensed under the MIT License.
You are free to modify and learn from it — responsibly.

🙋 Support

If you face issues:

Check EdgeDriver version mismatch

Ensure Selenium is installed

Verify driver path

Feel free to improve or refactor the scripts 🚀


---

If you want, I can also:
- ✅ Improve code structure
- ✅ Add `.gitignore`
- ✅ Convert this into a **legal-safe demo project**
- ✅ Add command-line arguments
- ✅ Add proxy / user-agent rotation (ethical testing)

Just tell me 👍
