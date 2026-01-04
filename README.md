# 🐍 python-quiz-game

Python command-line quiz game demonstrating user input, conditional logic, score tracking, and percentage calculation.

---

## 📄 View Project Report
👉 **[Python Quiz Game – Project Report.docx](https://github.com/user-attachments/files/24420852/Python.Quiz.Game.Project.Report.docx)
**  
*(Includes objectives, step-by-step execution, screenshots, and results)*

---

## 📌 Overview
This project is a Python-based interactive quiz game designed to demonstrate foundational programming concepts. The game runs in a command-line environment and interacts with the user through prompts, evaluates responses using conditional logic, tracks scores, and calculates a final percentage based on performance.

The program supports multiple execution paths, including early termination when the user chooses not to play, partial success when some answers are correct, and full success when all answers are answered correctly.

---

## 🎯 Objectives
- Build an interactive quiz game using Python
- Practice using `print()` and `input()` for user interaction
- Apply `if/else` statements for decision-making
- Track user performance using variables
- Calculate and display a final percentage score
- Demonstrate proper program flow control

---

## 🛠 Tools & Environment
- **Language:** Python 3  
- **IDE:** Visual Studio Code  
- **Execution:** Command Line / PowerShell  

---

## 🧪 Program Execution (Steps 1–4)

### Step 1: Program Initialization
The program displays a welcome message and prompts the user to decide whether they want to play. User input is stored in a variable and evaluated using conditional logic to determine whether the quiz should continue.

📸 *Source Code*  
<img width="1549" height="995" alt="1  Python Code" src="https://github.com/user-attachments/assets/49b0bb3e-a8c6-47bb-93ce-25905e6d5b25" />


---

### Step 2: User Declines to Play
If the user enters anything other than “yes,” the program exits immediately using the `quit()` function, demonstrating proper flow control.

📸 *Conditional Exit*  
<img width="927" height="143" alt="2  Shows what happens if you dont want to play" src="https://github.com/user-attachments/assets/97259ba9-e29e-4734-913e-aa788d789c29" />


---

### Step 3: Partial Correct Answers
The quiz runs and evaluates each response using `if/else` statements. In this execution, the user answers two out of three questions correctly, resulting in a final score of **66.67%**.

📸 *Partial Score Output*  
<img width="936" height="330" alt="3  Shows what happens if you only get couple right" src="https://github.com/user-attachments/assets/5f2893c1-5557-47fa-87b6-7c73381d59d9" />


---

### Step 4: All Correct Answers
When all questions are answered correctly, the program increments the score for each response and calculates a final percentage of **100%**, confirming that the scoring logic works as intended.

📸 *Perfect Score Output*  
<img width="941" height="410" alt="4  Shows what happens when all right" src="https://github.com/user-attachments/assets/65f9abe3-81af-4e2c-870d-8af73b6d9e0f" />


---

## 📊 Results
- Accurate score tracking based on user input  
- Case-insensitive input handling  
- Correct percentage calculation  
- Clean program termination when the user chooses not to play  

---

## 🚀 Future Enhancements
- Add more questions or quiz categories  
- Round percentage output for cleaner formatting  
- Randomize question order  
- Store scores in a file (CSV or JSON)  
- Build a graphical or web-based version  

---

## 🏁 Conclusion
The Python Quiz Game successfully demonstrates core Python programming concepts, including user interaction, conditional logic, variable management, and arithmetic operations. By supporting multiple execution paths, the program produces reliable and accurate results based entirely on user input, making it a strong foundational project for a programming portfolio.
