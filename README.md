# numpy-array-operations-assessment
Hands-on NumPy practice: arrays, broadcasting &amp; element-wise math applied to real-world-style weather and sales datasets.
# Introduction to NumPy — Hands-On Practice

A beginner-friendly Jupyter Notebook project that walks through the fundamentals of **NumPy**, Python's core library for numerical computing. The notebook progresses from basic array creation to element-wise arithmetic, broadcasting, and two mini real-world projects analyzing weather/temperature data.

---

## Project Overview

This assessment demonstrates practical NumPy skills through a series of exercises, a challenge task, and two mini-projects centered on temperature/weather data. It highlights why NumPy arrays are preferred over plain Python lists for numerical work — particularly for speed, memory efficiency, and clean element-wise operations.

---

## Contents

| Section | Description |
|---|---|
| **Exercise One** | Importing NumPy, creating 1-D and 2-D arrays, inspecting `dtype` |
| **Exercise Two** | Comparing Python lists vs. NumPy arrays for addition (concatenation vs. element-wise) |
| **Challenge** | Element-wise addition & subtraction of online vs. store sales data |
| **Exercise Three — Mini Project** | Weather Data Quick Analysis: comparing recorded vs. target temperatures over 7 days |
| **Mini Project Challenge** | Multi-location temperature analysis (Lagos, Abuja, Ibadan) with broadcasting and comparisons |
| **Bonus Challenge** | Predicting and verifying element-wise addition, subtraction, and multiplication on arrays |

---

## Tools & Technologies

- **Python 3**
- **NumPy** — core library used for array creation, element-wise operations, and broadcasting
- **Jupyter Notebook** — interactive environment for running and documenting the code

---

## Dataset

The datasets used are small, manually created arrays representing real-world-style numeric data:

- **Temperature readings** (single location, 7-day period):
  `[27.5, 29.0, 30.5, 28.0, 31.0, 32.5, 30.0]`
- **Target temperatures** (7-day period):
  `[28.0, 28.0, 29.0, 28.0, 30.0, 30.0, 29.0]`
- **Multi-location temperatures** (Lagos, Abuja, Ibadan — 5-day period):
  - Lagos: `[27.5, 29.0, 30.5, 28.0, 31.0]`
  - Abuja: `[25.0, 28.0, 29.5, 30.0, 32.0]`
  - Ibadan: `[26.5, 28.5, 29.0, 27.5, 30.0]`
- **Sales data** (Online vs. Store, Monday–Friday):
  - Online: `[20, 15, 10, 10, 30]`
  - Store: `[15, 16, 45, 10, 5]`

All data is synthetic and created for learning purposes only.

---

## Sample Output
<img width="1163" height="645" alt="h" src="https://github.com/user-attachments/assets/065d56e6-79a2-4d8b-836c-6056178f759e" />
<img width="1143" height="567" alt="h1" src="https://github.com/user-attachments/assets/b39cb451-6f8b-4842-b446-9580ecac798a" />
<img width="1122" height="555" alt="h2" src="https://github.com/user-attachments/assets/ce6dbcc9-13e1-4990-b582-76beed00b10d" />
<img width="1055" height="579" alt="h3" src="https://github.com/user-attachments/assets/287be555-8666-4884-91c3-0e8a3e650e04" />
<img width="1078" height="580" alt="h4" src="https://github.com/user-attachments/assets/781ddc3d-f65b-4bb8-b345-0123af9b1bac" />
<img width="1047" height="544" alt="h5" src="https://github.com/user-attachments/assets/6959fa3b-a509-4390-8bc2-cc4c37345ef1" />


## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```
2. Install the required dependency:
   ```bash
   pip install numpy jupyter
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `ASSESSMENT 14 (INTRODUCTION TO NUMPY).ipynb` and run the cells in order.

---

## Key Learnings

- NumPy arrays support **element-wise arithmetic**, unlike Python lists which concatenate on `+`.
- **Broadcasting** allows a scalar value to be applied across an entire array without writing loops.
- NumPy is significantly **faster and more memory-efficient** than plain Python lists, especially as data size grows.
- Simple array comparisons (subtraction) can reveal meaningful business/environmental insights, such as which days exceeded a target temperature or which location was warmest.

---

## Recommendations

- Extend the analysis with NumPy's statistical functions (`np.mean()`, `np.max()`, `np.min()`, `np.std()`) to summarize the data further.
- Visualize the temperature and sales trends using **Matplotlib** or **Seaborn** for clearer insights.
- Practice with larger, real-world datasets (e.g., CSV weather data) to better appreciate NumPy's performance advantages.
- Explore multi-dimensional arrays and matrix operations for more advanced use cases (e.g., linear algebra, image processing).

---

## Conclusion

This project reinforces the foundational role NumPy plays in data analysis and scientific computing in Python. Through simple, relatable examples — sales figures and weather temperatures — it shows how NumPy simplifies numerical operations that would otherwise require manual loops with plain Python lists, making code more concise, readable, and efficient.

---

## Author

**Emmanuel Mustapha**
 [mustaphaemmanuelola@gmail.com]
 [https://www.linkedin.com/in/mustaphaemmanuelola]

---

## License

This project is open-sourced for educational purposes. Feel free to fork, use, or adapt it for your own learning.
