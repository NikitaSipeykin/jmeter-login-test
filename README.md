# 🟠 JMeter Login Performance Test
This repository contains an example of a simple load test:  
1. Opening the main page  
2. Authorization using login and password  
3. Getting the profile page  
The scenario is parameterized — user data is taken from a CSV file.
---
## 📂 Project structure
```.

├── users.csv          
├── login_testplan.jmx 
└── README.md
```
---
## ⚙️ How to run
1. Run Apache JMeter.  
2. Open the `login_testplan.jmx` file.  
3. Make sure that `users.csv` is in the same directory.  
4. Run the plan.  
---
## 🧩 CSV (users.csv)
```csv
username,password
testuser1,pass1
testuser2,pass2
testuser3,pass3
```
---
## 🎯 Purpose
- Demonstration of parameterization in JMeter.  
- A basic example to get started, which can be expanded for real-world scenarios.  
