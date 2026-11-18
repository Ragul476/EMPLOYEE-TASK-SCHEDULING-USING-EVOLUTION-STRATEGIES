# Employee Task Scheduling Using Evolution Strategies

## 📌 Project Overview

This project implements an **Evolution Strategies (ES)** algorithm to solve the Employee Task Scheduling problem.

The main objective is to assign tasks to employees based on their skills while minimizing scheduling costs and balancing employee workloads.

Two Evolution Strategies are implemented and compared:

- (μ, λ) – Comma Strategy
- (μ + λ) – Plus Strategy

The project uses Python, NumPy, Pandas, and Matplotlib and can be executed directly in Google Colab.

## 🎯 Objectives

- Assign tasks to suitable employees based on their skills.
- Minimize employee-task skill mismatches.
- Reduce scheduling costs.
- Maintain balanced workloads among employees.
- Compare the performance of two Evolution Strategies.
- Visualize algorithm convergence using graphs.

## 🛠️ Technologies Used

- **Python** – Programming language
- **NumPy** – Numerical operations and population generation
- **Pandas** – Displaying scheduling results and comparison tables
- **Matplotlib** – Graph visualization
- **Random** – Mutation and selection operations

## 🧬 Algorithm Used

### 1. Evolution Strategies (μ, λ)

In this approach, new offspring are generated from the parent population. Only the best offspring are selected for the next generation.

### 2. Evolution Strategies (μ + λ)

In this approach, both parents and offspring are considered for selection. The best individuals are selected for the next generation.

## ⚙️ Project Implementation

The project follows these steps:

1. Initialize employee and task datasets.
2. Generate an initial population of possible task assignments.
3. Calculate the fitness of each individual.
4. Apply mutation to generate offspring.
5. Perform selection using both Evolution Strategies.
6. Repeat the process for multiple generations.
7. Compare the final scheduling results.

## 📊 Fitness Function

The fitness function calculates the scheduling cost based on:

- Employee skill mismatch penalty.
- Task duration and priority.
- Deadline penalty.
- Employee workload imbalance.

**Note:** A lower fitness value indicates a better scheduling solution.

## ▶️ How to Run the Project

### Option 1: Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Copy the complete Python code into a single cell.
4. Click the Run button.
5. View the scheduling results, comparison table, and convergence graph.

### Option 2: Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/employee-task-scheduling.git
   ```

2. Navigate to the project folder:

   ```bash
   cd employee-task-scheduling
   ```

3. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib
   ```

4. Run the Python program:

   ```bash
   python main.py
   ```

## 📈 Expected Output

The program generates:

- Optimized employee-task assignments.
- Employee skill matching information.
- Best fitness values.
- Comparison of (μ, λ) and (μ + λ) strategies.
- Execution time comparison.
- Evolution Strategy convergence graph.

## 📁 Project Structure

```text
Employee-Task-Scheduling/
│
├── main.py
├── README.md
└── requirements.txt
```

## 🔍 Conclusion

This project demonstrates how Evolution Strategies can be applied to employee task scheduling.

Both (μ, λ) and (μ + λ) strategies are implemented to compare their performance in finding better scheduling solutions.

The results help understand how evolutionary algorithms can optimize task allocation, reduce scheduling costs, and balance employee workloads.

## 👩‍💻 Author

**Ragul S.**

**Project:** Employee Task Scheduling Using Evolution Strategies

**Domain:** Artificial Intelligence – Evolutionary Computing
