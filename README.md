# 📘 Expectation Decider – Probability Project  
Simple Student-Friendly Analysis Using Python

This project analyzes student performance using probability concepts.  
A CSV dataset is used along with Python libraries to calculate empirical probability, random variables, mean, variance, Venn diagram, contingency table, conditional probability, and Bayes theorem.

---

## 📂 Project Files

- students_expectation_modified.csv  
- Expectation_Decider.ipynb  
- README.md  

---

## 🧰 Libraries Used

- pandas  
- numpy  
- matplotlib  
- matplotlib-venn  

Install required libraries using:

pip install pandas numpy matplotlib matplotlib-venn

---

## 📊 Dataset Description

The dataset contains student-level information with the following columns:

- study_hours – Number of study hours  
- attendance – Attendance percentage  
- group_discussion – Yes / No  
- previous_test_score – Previous exam marks  
- final_exam_pass – Pass / Fail  

Total records: 200 students.

---

## 🎯 Objective of the Project

To understand how:

- Study Hours  
- Attendance  
- Group Discussion  
- Previous Test Scores  

affect student exam performance using probability methods.

---

## 1. Probability

Probability means the chance of something happening.

Formula:

Probability = Favourable Outcomes / Total Outcomes

Example events:

- Student passes exam  
- Student studies more than 10 hours  
- Student joins group discussion  

---

## 2. Empirical Probability

Probability of passing exam is calculated using:

Probability of Pass = Passed Students / Total Students

This gives real probability based on dataset values.

---

## 3. Random Variable

Let X = number of students passing out of 3.

Possible values of X:

0, 1, 2, 3

Let:

p = probability of one student passing  
f = probability of one student failing  

Probability distribution:

- 0 students pass = f³  
- 1 student passes = 3pf²  
- 2 students pass = 3p²f  
- 3 students pass = p³  

---

## 4. Mean and Variance

Mean (Expected Value):

Shows average number of students passing out of 3.

Variance:

Shows how much the results vary from the mean.

Formulas used:

Mean = Σ(x × P(x))  
Variance = Σ((x − mean)² × P(x))

---

## 5. Venn Diagram

Two conditions are analyzed:

- Study hours greater than 10  
- Attendance greater than 80%  

The Venn diagram represents:

- Left circle → Students studying more than 10 hours  
- Right circle → Students with attendance above 80%  
- Overlapping area → Students satisfying both conditions  

---

## 6. Contingency Table

A contingency table is created using:

- Group Discussion  
- Final Exam Result  

This table is used to calculate:

- Joint Probability  
- Marginal Probability  
- Conditional Probability  

---

## 7. Joint, Marginal and Conditional Probability

Joint Probability:
Probability of Group Discussion AND Pass.

Marginal Probability:
Overall probability of Pass.

Conditional Probability:
Probability of Pass GIVEN Group Discussion.

---

## 8. Relationship Between Events

Group discussion and passing exam are DEPENDENT events because:

P(Pass | Group Discussion) ≠ P(Pass)

The probability changes when a condition is applied.

---

## 9. Bayes Theorem

Bayes formula:

P(A|B) = (P(B|A) × P(A)) / P(B)

Used to calculate:

P(Pass | High Attendance)

---

## 🧠 Final Summary

Students who:

- Study more  
- Attend classes regularly  
- Participate in group discussions  
- Perform well in previous tests  

have a higher probability of passing exams.

Group discussion and passing exam are dependent events.

---

## 🎓 Learning Outcomes

- Understanding probability  
- Random variables  
- Mean and variance  
- Venn diagram interpretation  
- Contingency tables  
- Conditional probability  
- Bayes theorem  
- Python-based data analysis  

---

## ✨ Author

Student Probability Mini Project  
Using Python and Jupyter Notebook
