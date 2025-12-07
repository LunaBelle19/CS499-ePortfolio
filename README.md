# CS-499 Computer Science Capstone ePortfolio

**Author:** Sanefa Amzad  
**Program:** B.S. Computer Science – Southern New Hampshire University  
**Course:** CS-499 Computer Science Capstone  
**Instructor:** Satish Penmatsa  

---

## About This Portfolio

This ePortfolio showcases my work for the CS-499 Computer Science Capstone.  
It highlights my growth as a computer-science professional through a single, fully enhanced artifact:

> **TreasureHuntGame (CS-370)** – a reinforcement-learning project that I redesigned, optimized, and extended across three enhancement categories:
> - Software design and engineering  
> - Algorithms and data structures  
> - Databases and persistence  

The goal of this portfolio is to demonstrate my ability to design, implement, document, and secure real-world software solutions while meeting the five CS-499 program outcomes.

---

## Featured Artifact: TreasureHuntGame (CS-370)

The **TreasureHuntGame** began as a 1D grid-world reinforcement-learning assignment in CS-370.  
An agent moves along a line of cells, learning to reach a treasure location using Q-learning.

Originally, the project:
- Lived in a single Python file
- Used basic Q-learning logic
- Stored no persistent data
- Had limited structure and minimal documentation

For the capstone, I selected this artifact and transformed it into a **modular, production-style reinforcement-learning system** with a focus on clean architecture, algorithmic efficiency, and persistent storage.

---

## Capstone Enhancements

### 1. Software Design & Engineering Enhancement

**Goal:** Refactor the original single-file script into a clean, maintainable, object-oriented architecture.

**Key Changes:**

- Introduced separate Python modules:
  - `Agent` – manages Q-learning updates and policy behavior
  - `Environment` – handles grid size, state transitions, rewards, and validation
  - `GameController` – coordinates training loops, hyperparameters, and convergence logic
  - `DatabaseHandler` – manages interaction with a SQLite database
  - `main.py` – ties all components together and runs experiments
- Applied software engineering principles:
  - Separation of concerns
  - Encapsulation and modularity
  - Improved readability and maintainability
  - Structured error handling and logging

This enhancement demonstrates my ability to redesign legacy or academic code into a scalable, professional architecture.

---

### 2. Algorithms & Data Structures Enhancement

**Goal:** Improve the learning efficiency and performance of the reinforcement-learning agent.

**Key Changes:**

- Implemented **ε-greedy decay** to balance exploration and exploitation
- Added an **adaptive learning rate** to stabilize training
- Replaced nested loops with **NumPy vectorization** for faster Q-updates
- Precomputed valid state transitions for **O(1)** action lookup
- Introduced **deterministic random seeds** for reproducible experiments
- Added **early stopping** based on reward plateaus to avoid unnecessary training

These changes improved the effective time complexity of training and produced faster, more stable convergence, showcasing my ability to design and evaluate algorithmic solutions.

---

### 3. Databases & Persistence Enhancement

**Goal:** Turn the project into a persistent, analyzable system using a relational database.

**Key Changes:**

- Integrated a **SQLite** database layer
- Designed tables to store:
  - Q-table values
  - Reward histories
  - Greedy paths
  - Episode-level metrics
- Implemented:
  - **Parameterized SQL queries** to prevent injection attacks
  - Normalized schema and appropriate indexing
  - Batch inserts and basic integrity checks
  - Structured exception handling for robustness

This enhancement demonstrates my understanding of database design, performance, and secure data handling in support of machine-learning workflows.

---

## Mapping to CS-499 Program Outcomes

This portfolio demonstrates the five CS-499 course outcomes:

1. **Collaborative environments**  
   - Clear documentation, code-review preparation, and communication of design decisions.

2. **Professional communication**  
   - Code review video, written narratives, and this ePortfolio organization tailored to technical and academic audiences.

3. **Algorithmic design and evaluation**  
   - Optimization of Q-learning, analysis of time complexity, and use of data structures to support constant-time transitions.

4. **Software engineering techniques**  
   - Object-oriented refactor, modular architecture, reusable components, error handling, and maintainable design.

5. **Security mindset**  
   - Input validation, parameterized SQL queries (to prevent SQL injection), defensive programming, and attention to safe data storage.

---

## How to Navigate This Repository

This repository is paired with a GitHub Pages site that serves as the visual ePortfolio:

- **GitHub Pages URL:**  
  `https://LunaBelle19.github.io/CS499-ePortfolio/`

Key items in this repository:

- `7-1 Final Project Submission.docx`  
  – Full professional self-assessment for the capstone

- `pirate-intelligent-agent.zip`  
  – Enhanced TreasureHuntGame source code (all three enhancements)

- `Amzad_Sanefa _ TreasureHuntGame (7-3 Submit Project Two).html`  
  – Original CS-370 artifact

- `2-2 Milestone One Code Review.docx` and video  
  – Code review of the original artifact and planned enhancements

- `3-2 Milestone Two - Enhancement One - Software Design and Engineering.docx`  
- `4-2 Milestone Three - Enhancement Two - Algorithms and Data Structure.docx`  
- `5-2 Milestone Four Enhancement Three Databases.docx`  
  – Narratives describing each enhancement and the course outcomes addressed

Together, these materials present a complete view of my growth as a computer scientist and my ability to design, implement, analyze, and secure computing solutions.

---

