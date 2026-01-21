# Applications-of-AI-in-IT-Final-Project
Final project covering Genetic Algorithms, Fuzzy Logic, and Machine Learning algorithms (Titanic).
# Applications of Artificial Intelligence in IT - Final Project

**Group Name:** F  
**Course:** Applications of Artificial Intelligence in IT  
**University:** WSB Merito University  
**Date:** January 2026

---

## 👥 Group Members
| Name | Student ID |
| :--- | :--- |
| **Dogancan Yucel** | 104009 |
| **Murat Emre Bulduk** | 103536 |
| **Denizhan Demirhan Yilmaz** | 105375 |

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

3. **`Group_F_Genetic_Algorithm.xlsx`** An Excel file demonstrating the step-by-step manual calculation logic for the Genetic Algorithm (Generation 1 & 2) with formulas.

---

## 🛠️ How to Run the Code
To reproduce the results:
1. Open the file `Group_F_Code.ipynb`.
2. Click the "Open in Colab" button (if viewing on GitHub) or upload it to [Google Colab](https://colab.research.google.com/).
3. Install the required fuzzy logic library by running the first cell:
   ```python
   !pip install scikit-fuzzy
