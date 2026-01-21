# Applications-of-AI-in-IT-Final-Project
Final project covering Genetic Algorithms, Fuzzy Logic, and Machine Learning algorithms (Titanic).


four parts = four topics = four tasks to-do:

1) DT = Decision Trees

2) NBC = Naive Bayes Classifier

3) GA = Genetic Algorithms

4) FL = Fuzzy Logic (fuzzy controler)

    please upload the code and the presentation of all four parts - in one report
    one submission per group (chosen above)
    include your names on title page
     
    on our last meeting / or earlier - show me the results personally
     
    for 3.0-3.5:
        DT - a classification problem found e.g. on kaggle
              - similar to the ones I've shown during classes (fruits, iris, titanic)
              - sth like cancer, diabetes, etc.
            understand the problem
            perform EDA - exploratory data analysis (like I did in Excel for titanic data)
            build a decision tree (and analyse the results)
        GA - backsack problem - for your dataset (see below)
            analyse at least 2 generations - in Excel
        NBC - "subscribers" example
            just do it in Excel
             
    for 4.0-4.5:
        the above plus...
        ...fuzzy controller - for your dataset (see below)
            describe the problem - using "human" language
            design the fuzzy sets - define memebership functions for inputs and outputs
            design the fuzzy rules
            check how it works - for at least two sample sets of input values
             
    for 5.0:
        the above plus...
        ...the backsack problem - implemented (in python) - demonstrated (for sample data) in your presentation
        ...and fuzzy controller - implemented (in python) and demonstrated
        ...and NBC - for your own data
            calculated "manually" - as I did for subscribers
            or implemented in python
             
    how to choose your datasets?
    (for backsack problem and fuzzy controller)
     
        sum up all students' album numbers in your group
        dataset nr for backsack problem = 1 + sum mod 15
        dataset nr for fuzzy controller = 1 + sum mod 29
        include the calculations in your presentation





# Applications of Artificial Intelligence in IT - Final Project

**Group Name:** F  
**Course:** Applications of Artificial Intelligence in IT  
**University:** WSB Merito University  
**Date:** January 2026

---

## 👥 Group Members
| Name | Student ID |
| :--- | :--- |
| **Dogancan Yucel** | 10**** |
| **Murat Emre Bulduk** | 103*** |
| **Denizhan Demirhan Yilmaz** | 105*** |

---

## 🚀 Project Overview
This repository contains the final project for the "Applications of AI in IT" course. The project demonstrates the implementation of three key Artificial Intelligence methodologies: **Genetic Algorithms**, **Fuzzy Logic**, and **Machine Learning**.

The specific variants for our group (Group F) were calculated based on the sum of our student IDs (**312,920**).

### 🧬 Part 1: Genetic Algorithms (Knapsack Problem)
* **Assigned Variant:** Dataset Set 6 (Capacity: 73)
* **Objective:** Solve the Knapsack Problem using evolutionary computation.
* **Methodology:**
  * Created a population of 20 individuals.
  * Applied **Penalty Function** for overloaded backpacks (Fitness = 0).
  * Used **Crossover** and **Mutation** to evolve the population.
* **Result:** Successfully optimized the solution, increasing the total value from Generation 1 to Generation 2.

### 🧠 Part 2: Fuzzy Logic Controller
* **Assigned Variant:** Topic 11 (Saw Blade Rotational Speed Control)
* **Objective:** Design a control system to adjust saw blade speed based on wood hardness and cutting time.
* **Logic:**
  * **Inputs:** Wood Hardness (0-10), Cutting Time (0-60 min).
  * **Output:** Rotational Speed (0-5000 RPM).
  * **Rules:** E.g., *IF Hardness is Hard THEN Speed is Slow.*
* **Tools:** Python `scikit-fuzzy` library.

### 🚢 Part 3: Machine Learning (Titanic Dataset)
* **Objective:** Predict passenger survival on the Titanic using classification algorithms.
* **Algorithms Implemented:**
  1. **Decision Tree Classifier** (Achieved Accuracy: ~80.97%)
  2. **Naive Bayes Classifier** (Achieved Accuracy: ~79.10%)
* **Tools:** `scikit-learn`, `pandas`, `matplotlib`.

---

## 📂 Repository Contents
This repository includes the following files:

1. **`Group_F_Final_Report.pdf`** The comprehensive project report containing all calculations, logic descriptions, charts, and final conclusions.

2. **`Group_F_Code.ipynb`** The Python source code (Jupyter Notebook) compatible with Google Colab. It contains the executable scripts for Genetic Algorithms, Fuzzy Logic simulation, and Titanic ML models.


---

## 🛠️ How to Run the Code
To reproduce the results:
1. Open the file `Group_F_Code.ipynb`.
2. Click the "Open in Colab" button (if viewing on GitHub) or upload it to [Google Colab](https://colab.research.google.com/).
3. Install the required fuzzy logic library by running the first cell:
   ```python
   !pip install scikit-fuzzy
