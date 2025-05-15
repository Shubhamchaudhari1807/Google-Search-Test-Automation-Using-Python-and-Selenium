
# 🔍 Google Search Automation with Selenium & Python

This project demonstrates how to automate a Google Search using **Python** and **Selenium WebDriver**. It takes a search topic as input, opens Google in Chrome, and displays the search results automatically using the Chrome browser.

---

## 📌 Features

- ✅ Automates browser using Selenium
- ✅ Accepts user input for the search topic
- ✅ Launches Chrome browser and performs a search
- ✅ Maximizes browser window for visibility
- ✅ Supports easy customization and enhancement (e.g., extracting search results)

---

## 🧰 Technologies Used

- Python 3.x  
- Selenium WebDriver  
- ChromeDriver  
- Google Chrome  

---

## 📁 Project Structure

📁 GoogleSearchAutomation


├── 📁chromedriver.exe # ChromeDriver binary

├── 📁testSearch.py # Main Python script

└── 📁README.md 

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   
        git clone https://github.com/yourusername/GoogleSearchAutomation.git
   
        cd GoogleSearchAutomation

2. Install dependencies
       
        pip install selenium

3. Download ChromeDriver
   
   Match the version with your Chrome browser:
   
       https://storage.googleapis.com/chrome-for-testing-public/136.0.7103.94/win64/chromedriver-win64.zip

4.   Update Driver Path
     
     Replace this line in testSearch.py:
            
          service = Service(r'C:\Path\To\chromedriver.exe')
      
     with your actual driver path.

🚀 How to Run

```

       python testSearch.py
```

👨‍💻 Author

Shubham Chaudhari

B.Tech Computer Engineering

[LinkedIn](https://www.linkedin.com/in/shubham-chaudhari-249877253/) | [GitHub](https://github.com/Shubhamchaudhari1807)



