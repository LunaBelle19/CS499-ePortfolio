# CS-499 Computer Science Capstone ePortfolio

**Author:** Sanefa Amzad  
**Program:** B.S. Computer Science – Southern New Hampshire University  
**Course:** CS-499 Computer Science Capstone  
**Instructor:** Satish Penmatsa  

---

## 📘 About This Portfolio

This ePortfolio showcases my work for the CS-499 Computer Science Capstone.  
It highlights my growth as a computer-science professional through a single, fully enhanced artifact:

### 🎯 **TreasureHuntGame (CS-370)**  
A reinforcement-learning project that I redesigned, optimized, and extended across three enhancement categories:

- **Software design and engineering**  
- **Algorithms and data structures**  
- **Databases and persistence**

The goal of this portfolio is to demonstrate my ability to design, implement, document, and secure real-world software solutions while meeting all five CS-499 program outcomes.

---

## 🏆 Featured Artifact: TreasureHuntGame (CS-370)

The TreasureHuntGame began as a simple 1D grid-world reinforcement-learning assignment in CS-370.  
An agent moves along a series of cells, learning to reach a treasure using Q-learning.

### Original limitations of the project:
- Contained in a **single Python script**
- Used only **basic Q-learning logic**
- **No persistent storage**
- **Minimal structure**, documentation, or scalability

For the capstone, I transformed this academic prototype into a modular, production-style reinforcement-learning system with clean architecture, efficient algorithms, and full persistent storage.

---

## 🚀 Capstone Enhancements

### **1. Software Design & Engineering Enhancement**

**Goal:** Refactor the original single-file script into a clean, maintainable, object-oriented architecture.

#### ✔ Key Changes
- Introduced modular Python components:
  - `Agent` – Q-learning policy and updates  
  - `Environment` – state transitions, rewards, validations  
  - `GameController` – training loops, hyperparameters, convergence checks  
  - `DatabaseHandler` – SQLite integration and persistence  
  - `main.py` – unified execution and experiment runner  
- Applied software engineering principles:
  - Separation of concerns  
  - Encapsulation and modularity  
  - Improved readability and maintainability  
  - Structured exception handling and logging  

This enhancement demonstrates my ability to redesign academic or legacy code into a scalable, professional software architecture.

---

### **2. Algorithms & Data Structures Enhancement**

**Goal:** Improve learning efficiency and training performance.

#### ✔ Key Changes
- Epsilon-greedy decay for adaptive exploration/exploitation  
- Adaptive learning rate for stability  
- Replaced nested loops with **NumPy vectorization**  
- **Precomputed transitions** for O(1) action lookup  
- Deterministic seeds for reproducibility  
- Early stopping based on reward plateaus  

These improvements reduced complexity and produced faster convergence, demonstrating strong algorithmic reasoning and data-structure optimization.

---

### **3. Databases & Persistence Enhancement**

**Goal:** Add a full relational storage system for long-term analysis.

#### ✔ Key Changes
- Integrated a **SQLite database layer**
- Designed tables for:
  - Q-table values  
  - Reward histories  
  - Greedy paths  
  - Episode-level metrics  
- Implemented:
  - **Parameterized SQL queries** to prevent injection attacks  
  - Normalized schema and indexing  
  - Batch inserts and integrity checks  
  - Structured exception handling  

This turned the project into a persistent, analyzable RL system suitable for real-world experimentation.

---

## 📚 Mapping to CS-499 Program Outcomes

### **1. Collaborative environments**
- Code review preparation, documentation, and communication of design decisions.

### **2. Professional communication**
- Code review video, written narratives, and organized ePortfolio content.

### **3. Algorithmic design and evaluation**
- Optimization of Q-learning, complexity analysis, and data-structure use.

### **4. Software engineering techniques**
- Object-oriented refactor, modular architecture, testing strategy, error handling.

### **5. Security mindset**
- Input validation, parameterized SQL queries, and safe data storage practices.

---

## 📂 How to Navigate This Repository

This repository pairs with my live GitHub Pages ePortfolio:

🔗 **GitHub Pages:**  
https://LunaBelle19.github.io/CS499-ePortfolio/

### Key Files Included

- **`7-1 Final Project Submission.docx`**  
  Professional self-assessment

- **`pirate-intelligent-agent.zip`**  
  Enhanced TreasureHuntGame (complete project)

- **`Amzad_Sanefa _ TreasureHuntGame (7-3 Submit Project Two).html`**  
  Original CS-370 artifact

- **Code Review (docx + mp4)**  
  Analysis and enhancement plan

- **Enhancement Narratives**  
  - `3-2 Enhancement One – Software Design & Engineering`  
  - `4-2 Enhancement Two – Algorithms & Data Structures`  
  - `5-2 Enhancement Three – Databases`  

Together, these materials provide a complete view of my growth as a computer scientist and my ability to design, implement, analyze, and secure computing solutions.

---


