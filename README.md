# Airbnb Market Analysis: Athens vs. Thessaloniki

This project performs a comparative data analysis of Airbnb listings between the two largest Greek cities: **Athens** and **Thessaloniki**. Using Python for data processing and Power BI for visualization, the study explores pricing trends, host behavior, and market evolution over time.

## 📁 Project Structure

- `airbnb.main.ipynb`: Jupyter Notebook containing the full data science workflow (cleaning, analysis, and visualization).
- `listings.csv`: Raw dataset containing Airbnb listings for Athens.
- `listings1.csv`: Raw dataset containing Airbnb listings for Thessaloniki.
- `AirBnb data.pbix`: Power BI dashboard file for interactive data exploration.

## 📊 Key Analysis Features

The analysis covers several critical aspects of the short-term rental market:

1. **Price Comparison**: Statistical analysis of prices per night in both cities, identifying luxury spots and budget-friendly neighborhoods.
2. **Temporal Trends**: Analysis of the `reviews_per_month` metric grouped by year to track the growth of the platform in Greece.
3. **Geospatial Analysis**: Mapping listings using latitude and longitude to identify high-density tourist clusters.
4. **Host Metrics**: Insights into host professionalization by analyzing the number of listings managed by single hosts.

## 🛠️ Technologies Used

- **Python 3.x**: Main programming language.
- **Pandas & NumPy**: For data manipulation and cleaning.
- **Matplotlib & Seaborn**: For static statistical visualizations.
- **Plotly Express**: For interactive charts within the notebook.
- **Power BI**: For advanced business intelligence reporting.

## 🚀 How to Run

1. **Prerequisites**: Ensure you have Python installed along with the following libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
