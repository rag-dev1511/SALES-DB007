# Sales & Revenue Analysis Dashboard

A Vanilla JavaScript and HTML5 dashboard designed as a hands-on learning project for **Data Visualization**, **KPI Tracking**, and **Business Insight Generation**. 

This lightweight, single-file dashboard demonstrates how to build interactive analytical tools without relying on heavy frontend frameworks. 

## 🎯 Learning Objectives

This project was built to explore the following core concepts:

### 1. Data Visualization & Charting
- **Library Integration:** Using [Chart.js](https://www.chartjs.org/) to render dynamic visualizations.
- **Visual Variety:** Implementing different chart types (Line, Doughnut, Bar) to represent different data dimensions (Trend analysis vs. Categorical share).
- **Responsive Design:** Ensuring charts and CSS Grid layouts adapt beautifully across desktop and mobile screens.

### 2. KPI Tracking (Key Performance Indicators)
- **Metric Aggregation:** Calculating high-level metrics like *Total Revenue*, *Units Sold*, and *Average Order Value* from granular dataset rows.
- **Contextual Comparisons:** Understanding how to compute delta percentages (e.g., ▲ 12.5% vs. prior period) to provide immediate context to stakeholders.

### 3. Interactive Analysis (Slicing & Dicing)
- **State Management:** Maintaining a global filter state (`region`, `category`, `date range`) using plain JavaScript objects.
- **Array Manipulation:** Using JavaScript's array methods (`.filter()`, `.reduce()`, `.map()`) to slice raw data based on user input.
- **Event-Driven UI:** Wiring up HTML `<select>` and `<input>` elements to trigger real-time re-renders of the dashboard.

### 4. Data Importing & Handling
- **CSV Parsing:** Utilizing [PapaParse](https://www.papaparse.com/) to convert user-uploaded `.csv` files into JSON objects readable by the dashboard.
- **Dynamic Data Structures:** Programmatically extracting unique labels (like new regions or product categories) directly from the imported dataset, rather than hardcoding arrays.

---

## 🚀 How to Run Locally

Because this project uses vanilla web technologies and client-side parsing, there is no build step, `npm install`, or backend required.

1. Clone or download this repository.
2. Open `sales_revenue_dashboard.html` directly in any modern web browser.
3. The dashboard will instantly load with a generated pseudo-random sample dataset.

## 📊 Importing Your Own Data

You can analyze your own custom data using the **IMPORT DATA (CSV)** feature located in the sidebar. 

1. Click **Download Sample CSV format** to get a template.
2. Fill the CSV with your own data. The expected columns are:
   - `product` (String, e.g., "Pro Laptop")
   - `category` (String, e.g., "Hardware")
   - `region` (String, e.g., "North America")
   - `month` (String, e.g., "Jan")
   - `monthIndex` (Number, `0` for Jan through `11` for Dec)
   - `units` (Number)
   - `revenue` (Number)
3. Click **Choose File** and upload your populated CSV. 
4. The dashboard's charts, tables, and dropdown filters will automatically update and adapt to reflect your new dataset!

---

## 🛠️ Built With

* **HTML5 / CSS3** (CSS Grid, Flexbox, Custom Variables)
* **JavaScript** (Vanilla ES6+)
* [**Chart.js**](https://www.chartjs.org/) - For data visualization
* [**PapaParse**](https://www.papaparse.com/) - For client-side CSV parsing

## 📝 License

This project is open-source and available for educational purposes. Feel free to fork, modify, break, and learn!
