# 📊 Graph Plotter Tool (Python)

A command-line utility to visualize your data in Python! Effortlessly plot **line graphs**, **bar charts**, and **scatter plots** from manual inputs or CSV files — no prior coding needed.

---

## ✨ Features

- Choose from **three graph types**
  - Line graph
  - Bar chart
  - Scatter plot
- **Input data manually** (X and Y values) or **load from a CSV file**
- **Automatic axis labeling, title, and grid**
- Easily **save your plot** as a PNG image or just display it
- Simple CLI prompts guide every step

---

## 🚀 How to Run

1. **Install Python** (requires Python 3)
2. **Install required packages:**
    ```
    pip install matplotlib pandas
    ```
3. **Save as `plotter.py`**
4. **Run in terminal:**
    ```
    python plotter.py
    ```

---

## 🧑‍💻 Usage Example

- Choose the type of graph (line, bar, scatter)
- Choose to enter data manually (type values) or load from a CSV file
- If loading from a CSV, make sure it has at least two columns for X and Y
- Preview the plot, decide whether to save (PNG) or just display

---

## 🗂️ How It Works

- Uses `matplotlib` for plotting and `pandas` for CSV handling
- Prompts for graph type, data entry method, and file saving
- Saves to file if requested — e.g., `graph.png`
- Works with all numeric datasets (CSV first two columns are used for X and Y)

---

## 📄 License

MIT License — free for learning, teaching, and tinkering.

---

A clean Python starter for bringing your data to life!
