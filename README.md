# 📊 Expectation Decider

A Python-based probability analysis project using a student performance dataset. This project demonstrates different concepts of probability and statistics using **Python, Pandas, NumPy, Matplotlib, and Matplotlib-Venn**.

## 📌 Project Overview

The **Expectation Decider** project analyzes student academic data to understand different probability concepts related to study hours, attendance, group discussion, previous test scores, and final exam results.

The project covers basic probability calculations as well as probability distributions, conditional probability, relationships between events, and Bayes' Theorem.

## 📂 Dataset

The dataset contains information about students and includes the following columns:

| Column                | Description                                          |
| --------------------- | ---------------------------------------------------- |
| `study_hours`         | Number of hours studied                              |
| `attendance`          | Attendance percentage                                |
| `group_discussion`    | Whether the student participated in group discussion |
| `previous_test_score` | Student's previous test score                        |
| `final_exam_pass`     | Final exam result: Pass or Fail                      |

The dataset contains **200 student records**.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Matplotlib-Venn
* Jupyter Notebook

## 📚 Concepts Covered

### 1. Basic Probability

Calculated probabilities such as:

* Probability of failing the exam
* Probability of passing the exam
* Probability of studying more than 10 hours and failing

For the complete dataset:

* Probability of Pass = **0.735**
* Probability of Fail = **0.265**

### 2. Empirical and Theoretical Probability

The project compares empirical probability using a random sample with theoretical probability calculated using the complete dataset.

* Empirical Probability of Passing = **0.76**
* Theoretical Probability of Passing = **0.735**

### 3. Random Variable and Probability Distribution

A random variable `X` represents the number of students who pass out of 3 randomly selected students.

Possible values:

```text
X = 0, 1, 2, 3
```

The probability distribution is calculated using the probability of passing and failing.

The project also calculates:

* Mean = **2.205**
* Variance = **0.584325**

### 4. Venn Diagram

A Venn diagram is created to compare two events:

* Students who study more than 10 hours
* Students who attend more than 80% of classes

The overlapping area represents students satisfying both conditions.

### 5. Contingency Table

A contingency table is created to analyze the relationship between:

* Group Discussion
* Final Exam Result

The table contains:

* Fail
* Pass
* Total

This helps analyze the relationship between participation in group discussions and exam results.

### 6. Joint Probability

Joint probability is calculated for events occurring together.

Example:

```text
Group Discussion = Yes AND Final Exam = Pass
```

The calculated joint probability is:

```text
0.380
```

### 7. Marginal Probability

The marginal probability of passing the final exam is calculated:

```text
P(Pass) = 0.735
```

### 8. Conditional Probability

The project calculates the probability of passing the exam given that a student participated in group discussion.

```text
P(Pass | Group Discussion = Yes)
= 0.8172
```

or approximately:

```text
81.72%
```

### 9. Independent and Dependent Events

The project compares:

```text
P(Pass)
```

with:

```text
P(Pass | Group Discussion = Yes)
```

The values are different, which is used in the project to discuss the relationship between the two events.

The events are also not mutually exclusive because a student can participate in group discussion and pass the exam.

### 10. Bayes' Theorem

Bayes' Theorem is applied using high attendance and exam results.

The project calculates:

```text
P(Pass | High Attendance)
```

Result:

```text
0.87857
```

or approximately:

```text
87.86%
```

## 📈 Project Workflow

```text
Load Dataset
     ↓
Explore Student Data
     ↓
Calculate Basic Probabilities
     ↓
Empirical & Theoretical Probability
     ↓
Probability Distribution
     ↓
Mean & Variance
     ↓
Venn Diagram
     ↓
Contingency Table
     ↓
Joint Probability
     ↓
Marginal Probability
     ↓
Conditional Probability
     ↓
Relationship Between Events
     ↓
Bayes' Theorem
```

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/expectation-decider.git
```

Move into the project folder:

```bash
cd expectation-decider
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib matplotlib-venn jupyter
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
Expectation Decider .ipynb
```

## 📁 Project Structure

```text
Expectation-Decider/
│
├── Expectation Decider .ipynb
├── expectation_decider_dataset.csv
└── README.md
```

## 🎯 Objective

The main objective of this project is to apply probability and statistics concepts to a real student-performance dataset using Python.

The project demonstrates how probability can be used to analyze student performance, study habits, attendance, group discussion participation, and exam outcomes.

## 🔑 Key Results

| Analysis                                       |   Result |
| ---------------------------------------------- | -------: |
| Probability of Passing                         |    73.5% |
| Probability of Failing                         |    26.5% |
| Empirical Probability of Passing               |      76% |
| Mean of Students Passing                       |    2.205 |
| Variance                                       | 0.584325 |
| P(Pass | Group Discussion = Yes)               |   81.72% |
| P(Pass | High Attendance) using Bayes' Theorem |   87.86% |

## 👩‍💻 Author

**Disha Chaudhari**

This project was created for learning and applying probability, statistics, and Python data analysis concepts.

## ⭐ Conclusion

This project demonstrates how Python can be used to perform probability analysis on student performance data. It covers basic probability, empirical and theoretical probability, probability distributions, Venn diagrams, contingency tables, joint probability, marginal probability, conditional probability, and Bayes' Theorem.
