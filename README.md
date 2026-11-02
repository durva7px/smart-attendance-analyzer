# Smart Attendance Analysis (RCOEM)

This is a project we built during out sixth semester as a part of Project Based Learning. A fully automated system that scrapes attendance data from the college website and provides insights on how many classes to attend or skip to maintain the required attendance percentage.

Built by — [Durva Deshpande](https://github.com/durva7px) & [Yadhnika Wakde](https://github.com/SuzanTurner)

# Demo ⬇️

<img width="400" height="225" alt="attendance analyzer" src="https://github.com/user-attachments/assets/f2926280-cd00-4432-b9a5-f4a55e13fd8b" />

# 📌 Features

1. **Automated Attendance Scraping** – Uses Selenium to log in and fetch attendance data.
2. **Smart Recommendation System** – Calculates how many classes a student can skip or needs to attend.
3. **Web Extension & Website** - Available as both a web-application and browser extenstion
4. **Default Login Credentials** - No separate account creation required. Just login with your existing JUNO credentials

### Extension Link 🔗
https://chromewebstore.google.com/detail/kiponejpbjejdccpcebjkjahlacjnngh?utm_source=item-share-cb

---

# 🛠 Setup Instructions

### 1️⃣ Clone the Repository

```powershell
git clone https://github.com/durva7px/smart-attendance-analyzer.git
```


### 2️⃣ Install Dependencies

Make sure you have Python installed (preferably 3.9+). Then install the required dependencies:

```powershell
pip install -r requirements.txt
```


### 3️⃣ Download and Set Up ChromeDriver

Download the Chromedriver folder in the repo. Make sure to enter the correct path in the python script.


### 4️⃣ Check the files

Make sure the files are in the following format:

```powershell

📂 Attendance-Analysis-PBL
│── 📂 templates/
          │── attendance.html
          │── error.html
          │── login.html
          │── cgpa.html
          │── mail.html
│── main.py                
│── requirements.txt        
│── README.md  
```

### 5️⃣ Run the Project 🚀

```powershell
python main.py
```

--- 

# How this works ⚡

1. Log in with user credentials
2. Opens the college website via Selenium
3. Scrape attendance data
4. Recommendation algorithms provide a comprehensive analysis of your Attendance Situation ✅




