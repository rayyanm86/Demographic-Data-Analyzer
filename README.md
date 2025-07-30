# Demographic Data Analyzer
This project is part of the **freeCodeCamp Data Analysis with Python Certification**. It analyzes demographic data using the **Pandas** library and answers a set of questions about income, education, work hours, and more based on the **Adult Income Dataset**.

---

## 📂 Dataset

The dataset used is `adult.data.csv`, which includes features such as:

* Age
* Workclass
* Education
* Occupation
* Race
* Sex
* Hours-per-week
* Native-country
* Salary

---

## 📊 Output Summary

Here are the findings from the dataset analysis:

* **Number of each race:**

  ```
  White                 27816  
  Black                  3124  
  Asian-Pac-Islander     1039  
  Amer-Indian-Eskimo      311  
  Other                   271  
  ```

* **Average age of men:** `39.4`

* **Percentage with Bachelors degrees:** `16.4%`

* **Percentage with higher education that earn >50K:** `46.5%`

* **Percentage without higher education that earn >50K:** `17.4%`

* **Minimum work time:** `1 hour/week`

* **Percentage of rich among those who work minimum hours:** `10.0%`

* **Country with highest percentage of rich:** `Iran`

* **Highest percentage of rich people in a country:** `41.9%`

* **Top occupation in India for >50K earners:** `Prof-specialty`

---

## 🧪 Functionality

The script uses:

```python
calculate_demographic_data(print_data=True)
```

This function:

* Loads the dataset using `pandas`.
* Performs filtering and aggregation to answer demographic questions.
* Returns a dictionary with results and optionally prints them.

---

## ⚙️ Requirements

Install the required Python package:

```bash
pip install pandas
```

---

## ▶️ Running the Code

Ensure `adult.data.csv` is in the same directory as the script and run:

```bash
python demographic_data_analyzer.py
```

---

## 📁 File Structure

```
project/
│
├── adult.data.csv                 # Dataset file
├── demographic_data_analyzer.py  # Main analysis script
└── README.md                      # Project documentation
```

---

## 📌 Notes

* This project follows the specifications provided by **freeCodeCamp** for certification.
* Data cleaning is minimal; missing or unknown values (`?`) are not handled separately.
