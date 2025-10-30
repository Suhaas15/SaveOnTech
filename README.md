# SaveOnTech
*A “Trivago for Techies” 💡 — compare tech product prices in one place*

---

## 📘 Table of Contents  
- [Overview](#overview)  
- [Motivation](#motivation)  
- [Key Features](#key-features)  
- [Architecture & Tech Stack](#architecture--tech-stack)  
- [Getting Started](#getting-started)  
- [Usage](#usage)  
- [Future Work](#future-work)  
- [Contributing](#contributing)   
- [Contact](#contact)  

---

## 🧩 Overview  
**SaveOnTech** is a web-based application that helps users **compare tech product prices across multiple retailers** — think of it as the **Trivago for tech shoppers**.  
It aggregates price data from various online stores, tracks historical changes, and helps users make data-driven purchasing decisions.

Whether you’re buying a laptop, monitor, or graphics card, SaveOnTech ensures you never overpay again.

---

## 💡 Motivation  
Online tech pricing fluctuates rapidly, and each retailer offers different discounts or bundles.  
Manually checking every site is time-consuming — and existing price-comparison tools often cover only a limited number of vendors or categories.  

**SaveOnTech** solves this by:
- Centralizing product search and comparison in one platform.  
- Tracking price history to show if now is a good time to buy.  
- Notifying users when prices drop below their desired threshold.

---

## 🚀 Key Features  
- 🛒 **Cross-platform product search** — find items across multiple retailers.  
- 💰 **Real-time price comparison** with lowest price highlighted.  
- 📈 **Price history tracking** — visualize historical data to see trends.  
- 🔔 **Custom price alerts** — get notified when products hit your target price.  
- 🧭 **Category-based browsing** — laptops, accessories, smartphones, and more.  
- 📱 **Responsive UI** — optimized for both desktop and mobile.  

---

## ⚙️ Architecture & Tech Stack  

### **Frontend**
- HTML, CSS (responsive layout)  
- JavaScript (dynamic search & UI updates)  

### **Backend**
- Python (core logic, scraping/APIs, price tracking)  
- Flask (or similar) to serve routes and manage data  
- SQLite / PostgreSQL (for storing product and price data)  

### **Libraries & Tools**
- BeautifulSoup, Requests (for scraping, if APIs unavailable)  
- Cron / Scheduler for periodic data updates  
- GitHub for version control  

**Why this stack?**  
Python offers clean, reliable tools for data scraping and automation.  
The minimal web stack keeps deployment simple while remaining scalable for future enhancements like ML-based predictions.

---

## 🧠 Getting Started  

### **1. Prerequisites**
- Python 3.8+  
- Git  
- Virtual environment (`venv` or `conda`)  
- SQLite or other lightweight DB (default setup uses SQLite)

### **2. Installation**
```bash
# Clone the repository  
git clone https://github.com/Suhaas15/SaveOnTech.git
cd SaveOnTech

# (Optional) Create and activate a virtual environment  
python3 -m venv venv
source venv/bin/activate       # Mac/Linux
venv\Scripts\activate          # Windows

# Install dependencies  
pip install -r requirements.txt

# Initialize the database (if applicable)
python setup_db.py
```
---

##   Run the application

### Start the backend server  
```bash
python app.py
```
  
---

## 🧭 Usage  
1. Open the app in your browser.  
2. Enter a product name (e.g., “MacBook Air M2”) in the search bar.  
3. View a table comparing prices across different vendors.  
4. Click on a result to view detailed product information and price history.  
5. Set a custom price-drop alert to be notified when the price hits your target.  
6. (Optional) Log in to save products to your personal watchlist.  

---

## 🔮 Future Work  
- 🌍 Add support for more international and niche tech retailers.  
- 📱 Develop a dedicated mobile app using React Native or Flutter.  
- 🤖 Integrate machine learning to predict upcoming price drops.  
- 🧑‍💻 Add authentication for personalized dashboards and saved searches.  
- 💬 Introduce community reviews and product recommendations.  
- 🎨 Enhance UI/UX with modern frameworks (React + Tailwind).  
- ☁️ Deploy to a public cloud service (e.g., AWS, Render, or Vercel).  

---

## 🤝 Contributing  
Contributions are always welcome!  
To get started:
1. **Fork** the repository.  
2. **Create a new branch** (`feature/your-feature-name`).  
3. **Commit** your changes with clear, descriptive messages.  
4. **Push** to your fork and open a **Pull Request**.  

Please make sure your code follows existing style conventions and that all tests pass before submitting a PR.

---

## 👤 Contact  
**Created by:** [Suhaas Srungavarapu](https://github.com/Suhaas15)  
🎓 M.S. Computer Science & Engineering @ Santa Clara University  
💼 Former Software Engineer @ HSBC  
📧 Email: *[suhaas15032001@gmail.com]*   

> “SaveOnTech aims to make tech shopping smarter, not harder.”

---
