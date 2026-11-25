# 🏨 Hotel Booking Demand Analysis – Seven Stages of Data Visualization

## 📌 Project Overview

This project focuses on exploring and visualizing hotel booking data using Python. It follows the **Seven Stages of Data Visualization** to understand booking patterns, analyze customer behaviour and identify meaningful trends in hotel reservations.

The analysis uses the Hotel Booking Demand dataset, which contains booking information for City Hotels and Resort Hotels between July 2015 and August 2017.

The project demonstrates how raw data can be acquired, parsed, filtered, explored, represented, refined and made interactive through data visualization techniques.

## 🎯 Project Objectives

- Understand hotel booking patterns across different hotel types.
- Analyze booking and cancellation trends.
- Explore customer booking information and country-wise bookings.
- Examine meal requirements and length of hotel stays.
- Analyze Average Daily Rate (ADR).
- Create meaningful visualizations to identify patterns and trends.
- Apply the Seven Stages of Data Visualization using Python.

## 📊 Dataset Information

**Dataset Name:** Hotel Booking Demand

**Dataset Source:** [Kaggle – Hotel Booking Demand](https://www.kaggle.com/code/mohammadsabeti/hotel-booking-dataset-analysis)

**Original Dataset Details:**
- Total Records: 119,390
- Total Columns: 36
- Hotel Types: City Hotel and Resort Hotel
- Booking Period: 1 July 2015 – 31 August 2017
- File Format: CSV

The dataset includes information about hotel types, booking status, arrival dates, customer details, meal preferences, length of stay, country of origin and Average Daily Rate (ADR).

**Data Filtering:** After removing six irrelevant columns, the analysis focuses on bookings from the year 2016, resulting in 56,707 records.

## 🛠️ Technologies & Libraries Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Jupyter Notebook | Development and analysis environment |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Plotly | Interactive visualizations |
| Squarify | Treemap visualizations |

## 🔍 Seven Stages of Data Visualization

### 1. Data Acquire

The Hotel Booking Demand dataset was obtained from Kaggle.

It contains 119,390 observations representing bookings for City Hotels and Resort Hotels, including both completed and cancelled bookings.

### 2. Parse

The CSV dataset was loaded into a Pandas DataFrame using `pd.read_csv()`.

The structure of the dataset was examined using:
- `df.info()`
- `df.head()`

This helped understand the dataset's columns, data types and structure.

### 3. Filter

In this stage, irrelevant columns were removed from the dataset.

The following columns were dropped:
- name
- email
- phone-number
- credit_card
- company
- reservation_status_date

The dataset was then filtered to focus on bookings from the year 2016.

The filtered DataFrame contains 56,707 records.

### 4. Mine

Exploratory Data Analysis (EDA) was performed to understand the dataset and identify relevant patterns.

The following components were explored:

- Type of hotel
- Number of bookings
- Cancellation status
- Guests coming through agents
- Meal requirements
- Stays in week and weekend nights
- Reservation status
- Average Daily Rate (ADR)

Descriptive statistics were also examined using `df1.describe()`.

### 5. Represent

Data was represented using different charts and visualizations to communicate booking patterns and trends.

Visualizations included:

- Bar Chart – Number of Bookings per Year by Hotel Type.
- Sunburst Chart – Booking and Cancellation Status by Hotel Type (2016).
- Treemap – Top 20 Countries by Hotel Bookings (2016).
- Grouped Bar Chart – Average Daily Rate (ADR) by Hotel Type and Month (2016).

### 6. Refine

The visualizations were refined to improve readability and presentation.

Improvements included:
- Adding appropriate chart titles.
- Using different colours to distinguish categories.
- Adding labels and annotations.
- Adjusting chart sizes and layouts.
- Improving the presentation of treemap visualizations.

### 7. Interact

Interactive visualizations were created using Plotly.

The interactive charts allow users to explore the data through features such as:
- Hover information.
- Interactive chart elements.
- Visual exploration of booking and cancellation status.
- Comparison of monthly ADR across hotel types.

## 📈 Key Analysis Areas

The project focuses on understanding:

1. Booking distribution between City Hotels and Resort Hotels.
2. Booking and cancellation status.
3. Country-wise hotel bookings.
4. Monthly Average Daily Rate (ADR).
5. Differences in booking patterns across hotel types.

## 📁 Project Structure

```text
hotel-booking-demand-visualization/
│
├── README.md
├── hotel-booking-demand-visualization.ipynb
├── requirements.txt
├── .gitignore
│
├── data/
│   └── README.md
│
└── images/
```

## ⚙️ Installation and Execution

### 1. Clone the repository

```bash
git clone https://github.com/AnkitaKurade/hotel-booking-demand-visualization.git
```

### 2. Navigate to the project directory

```bash
cd hotel-booking-demand-visualization
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Download the dataset

Download the Hotel Booking Demand dataset from Kaggle.

Refer to `data/README.md` for dataset download instructions.

Place the required CSV file in the project directory's data folder.

### 5. Open Jupyter Notebook

```bash
jupyter notebook
```

Open `hotel-booking-demand-visualization.ipynb` and execute the cells.

**Note:** The notebook's dataset loading path should be updated to `data/hotel_booking.csv` if you store the CSV inside the data folder.

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Acquiring and loading real-world datasets.
- Understanding data structures and data types.
- Filtering and manipulating data using Pandas.
- Performing exploratory data analysis.
- Analyzing hotel booking trends and patterns.
- Creating different types of data visualizations.
- Refining charts for better communication.
- Building interactive visualizations using Plotly.

## 👩‍💻 Author

**Ankita Kurade**
**Joylin Nadar**

⭐ If you find this project useful, feel free to explore the notebook and share your feedback.
