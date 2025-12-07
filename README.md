# CS-499 Computer Science Capstone ePortfolio  

**Author:** Sanefa Amzad  
**Program:** B.S. Computer Science – Southern New Hampshire University  
**Course:** CS-499 Computer Science Capstone  
**Instructor:** Satish Penmatsa  

---

# 🎥 Code Review Video  

**Note:**  
Due to GitHub’s file-size limitations, the code review video is hosted externally.  
You may view the full presentation using the link below:

👉 **[▶ Watch Code Review Video](https://www.canva.com/design/DAG5JsKCWB8/tH_HyREzp4fAKcLRVDJ8Bw/watch?utm_content=DAG5JsKCWB8&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hb06792a3cb)**

---

# 🌟 About This Portfolio  

This ePortfolio showcases my work for the **CS-499 Computer Science Capstone**.  
It highlights my growth as a computer-science professional through a single, fully enhanced artifact:

### **TreasureHuntGame (CS-370)**  
A reinforcement-learning project that I redesigned, optimized, and extended across three enhancement categories:

- **Software design & engineering**  
- **Algorithms & data structures**  
- **Databases & persistence**

The portfolio demonstrates my ability to design, implement, analyze, and secure real-world software solutions while meeting all **five CS-499 program outcomes**.

---

# 🧩 Featured Artifact: TreasureHuntGame (CS-370)

The TreasureHuntGame began as a simple **1D grid-world reinforcement-learning** assignment in CS-370, where an agent learns to reach a treasure using Q-learning.

### **Original limitations:**
- Single Python file  
- Basic Q-learning logic  
- No persistent storage  
- Minimal structure  
- Limited documentation  

### **Capstone Objective:**  
Convert this academic script into a **scalable, production-style reinforcement-learning system** with clean architecture, improved performance, and persistent storage.

---

# 🚀 Capstone Enhancements  

## **1. Software Design & Engineering Enhancement**  
**Goal:** Refactor the original single-file script into a clean, modular, object-oriented system.

### 🔧 Key Improvements  
- Created an object-oriented module structure:
  - `Agent` – learning behavior and Q-updates  
  - `Environment` – rewards, transitions, and validation  
  - `GameController` – training loop, hyperparameters, convergence logic  
  - `DatabaseHandler` – SQLite storage  
  - `main.py` – program entry point  
- Applied software engineering principles:
  - Separation of concerns  
  - Modularity and encapsulation  
  - Improved readability and maintainability  
  - Logging and structured exception handling  

---

## **2. Algorithms & Data Structures Enhancement**  
**Goal:** Increase training performance and reinforcement-learning stability.

### 🔧 Key Improvements  
- Implemented **ε-greedy decay**  
- Added **adaptive learning rate**  
- Replaced nested loops with **NumPy vectorization**  
- Precomputed transitions for **O(1)** lookups  
- Added deterministic seeds  
- Early stopping based on reward plateau  

### ⭐ Result  
Time complexity improved from **O(E × T × A)** to **O(E × T)**, producing faster and more stable convergence.

---

## **3. Databases & Persistence Enhancement**  
**Goal:** Add persistent storage for analysis and long-term RL behavior tracking.

### 🔧 Key Improvements  
- Integrated **SQLite relational database**  
- Designed tables for:
  - Q-table values  
  - Reward histories  
  - Episode metrics  
  - Greedy paths  
- Implemented:
  - **Parameterized SQL queries** (prevents SQL injection)  
  - Schema normalization and indexing  
  - Batch inserts  
  - Data-integrity validation  
  - Structured exception handling  

### ⭐ Result  
A persistent and analyzable machine-learning system suitable for real-world workflows.

---

# 🎓 Mapping to CS-499 Program Outcomes  

### **1. Collaborative Environments**  
Clear documentation, code review preparation, and structured communication of design decisions.

### **2. Professional Communication**  
Code review video, narratives, and this organized ePortfolio.

### **3. Algorithmic Design & Evaluation**  
Optimization of Q-learning, complexity improvements, and structured RL logic.

### **4. Software Engineering Techniques**  
Object-oriented refactor, modular design, maintainability, scalability.

### **5. Security Mindset**  
SQL parameterization, input validation, defensive programming, and safe data handling.

---

# 📁 Repository Navigation  

This repository works together with my GitHub Pages ePortfolio:

🔗 **GitHub Pages Site:**  
https://LunaBelle19.github.io/CS499-ePortfolio/
https://github.com/LunaBelle19/CS499-ePortfolio?tab=readme-ov-file

### 📦 Included Files  

| File | Description |
|------|-------------|
| **7-1 Final Project Submission.docx** | Professional self-assessment |
| **pirate-intelligent-agent.zip** | Enhanced TreasureHuntGame source code |
| **Amzad_Sanefa_TreasureHuntGame.html** | Original CS-370 artifact |
| **2-2 Milestone One Code Review.docx** | Code review write-up |
| **3-2 Enhancement One – Software Engineering.docx** | Narrative |
| **4-2 Enhancement Two – Algorithms.docx** | Narrative |
| **5-2 Enhancement Three – Databases.docx** | Narrative |
| **Code Review Video (external link)** | Canva-hosted presentation |

These files present a full and complete demonstration of my technical growth and capabilities as a computer scientist.

---


