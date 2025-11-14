# weather_analyser
This project visualizes and explores the relationship between **temperature** and **pollution levels** over time using Python. It leverages powerful data analysis and visualization libraries such as **NumPy**, **Pandas**, **Matplotlib**, and **mplcursors** to deliver an interactive experience.

## Features

### 1. Temperature Trend Over Time

Plots a smooth line graph showing how temperature has changed across the given time period.

### 2. Pollution Trend Over Time

Displays pollution level fluctuations over time in a clear and readable chart.

### 3. Temperature vs Pollution Scatter Plot

Shows the relationship between temperature and pollution using a scatter plot.

### 4. Interactive Hover Feature (via mplcursors)

When the user hovers over any plotted point, a tooltip displays:

* Exact temperature
* Pollution value
* Timestamp (if included in dataset)

This interactivity helps users better understand correlations and anomalies.

---

## Technologies Used

* **NumPy** – numerical operations
* **Pandas** – data cleaning, manipulation, and preparation
* **Matplotlib** – visualization (line chart, scatter plot)
* **mplcursors** – interactive hover tooltips

---

## Project Structure

```
project-folder/
│
├── data/
│   └── data.csv
|   └── cleaned_data.csv
└── main.py
└── data_visualizer.py
└── data_loader.py
└── data_cleaner.py
└── README.md
```

---

## How to Run

1. Install dependencies:

```bash
pip install numpy pandas matplotlib mplcursors
```

2. Place your dataset inside the `data/` folder.

3. Run the project:

```bash
python main.py
```

## Notes

* Ensure your dataset contains temperature, pollution, and time columns.
* You may customize colors, labels, or tooltip text inside the script.

---

## 🙌 Contribution

Feel free to submit issues or pull requests to improve the project!

---

## License

MIT License — free to use, modify, and distribute.

