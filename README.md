# 🎓 Simple Student Grade Calculator

A beginner-friendly Python project that calculates a student's grade based on their marks.  

This project demonstrates how to use **if-else statements**, **loops**, **functions**, and **basic error handling** in Python.

---

## 🧠 **Project Overview**

The **Student Grade Calculator** takes marks (0–100) as input and:

- Validates the input range

- Calculates the grade (A, B, C, D, or F)

- Displays an encouraging feedback message for each grade
  

This project is part of **Week 2: Making Decisions & Repeating Tasks in Python** — where we learn about:
- `if-else` statements
  
- Comparison operators (`==`, `>`, `<`, etc.)
  
- Loops (`for`, `while`)
  
- Functions and error handling
  

---

## 🚀 **Features**

✅ Takes user input for marks  
✅ Validates the input (must be between 0 and 100)  
✅ Uses conditional statements to determine grades  
✅ Prints encouraging feedback messages  
✅ Easy to understand — perfect for Python beginners  

---

example code:

marks = float(input("Enter your marks (0-100): "))

if marks < 0 or marks > 100:

    print("❌ Invalid input! Please enter marks between 0 and 100.")
    
else:

    if marks >= 90:
    
        grade = "A"
        
        message = "Excellent work! 🌟"
        
    elif marks >= 80:
    
        grade = "B"
        
        message = "Great job! Keep it up! 👍"
        
    elif marks >= 70:
    
        grade = "C"
        
        message = "Good effort! You can do even better! 💪"
        
    elif marks >= 60:
    
        grade = "D"
        
        message = "You passed, but aim higher next time! 🎯"
        
    else:
    
        grade = "F"
        
        message = "Don’t give up — keep practicing! 📘"
        

    print(f"\nYour Grade: {grade}")
    
    print(f"Feedback: {message}")
    

    
example output:

🎓 Welcome to the Student Grade Calculator 🎓
----------------------------------------
Enter your marks (0-100): 85

Your Grade: B
Feedback: Great job! Keep it up! 👍

