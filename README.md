# 💻 Laptop Price Prediction

A machine learning project that predicts laptop prices based on various specifications such as processor, RAM, storage, operating system, and more. This project includes web scraping from Flipkart, data cleaning, exploratory data analysis, and multiple regression models.

## 📊 Project Overview

This project aims to build a predictive model that can estimate laptop prices based on their specifications. The project follows a complete data science pipeline from data collection to model deployment.

### Business Problem
Predicting the price of laptops based on their specifications to help consumers make informed purchasing decisions and assist sellers in competitive pricing.

### Machine Learning Problem
This is a **regression problem** where we predict a continuous value (laptop price) based on multiple features.

## 🎯 Features

- **Web Scraping**: Automated data collection from Flipkart e-commerce website
- **Data Cleaning**: Handling missing values, outliers, and data standardization
- **Exploratory Data Analysis**: Comprehensive statistical analysis and visualizations
- **Feature Engineering**: Creating meaningful features from raw data
- **Machine Learning Models**: Multiple regression algorithms tested and compared
- **Model Evaluation**: Performance metrics including R² Score, MAE, and RMSE

## 📁 Project Structure

```
Laptop-Price-Prediction/
│
├── Main Code.ipynb                      # Main analysis and ML pipeline
├── web scrapping Code.ipynb             # Web scraping scripts
├── cleaned_file.csv                     # Processed dataset
├── uncleaned_file.csv                   # Raw scraped data
├── create_simple_dashboard.py           # Excel dashboard generator script
├── Laptop_Price_Dashboard_Interactive.xlsx  # Interactive Excel dashboard with charts
├── BDA Report.pdf                       # Project report
├── Laptop Price Prediction PPT.pptx     # Presentation
└── README.md                            # Project documentation
```

## 🛠️ Technologies Used

- **Python 3.x**
- **Data Collection**: Selenium, BeautifulSoup4, webdriver-manager
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Web Scraping**: Selenium WebDriver, Chrome Driver

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Laptop-Price-Prediction.git
cd Laptop-Price-Prediction
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
pip install selenium beautifulsoup4 webdriver-manager
```

3. For web scraping, ensure you have Chrome browser installed.

## 🚀 Usage

### Running the Web Scraper
```python
# Open web scrapping Code.ipynb
# Run the cells to scrape laptop data from Flipkart
# Data will be saved as CSV files
```

### Running the Analysis
```python
# Open Main Code.ipynb
# Update the file path in the data loading cell
# Run all cells to see the complete analysis and model results
```

### Creating Excel Dashboard
```bash
# Run the dashboard generator script
python create_simple_dashboard.py

# This creates Laptop_Price_Dashboard_Interactive.xlsx with:
# - Dashboard overview with key statistics
# - Raw data sheet with filters
# - Brand analysis with charts
# - Processor comparison
# - Price range distribution
# - Interactive slicers for filtering
```

## 📈 Models Implemented

The project compares multiple regression algorithms:

1. **Linear Regression**
2. **Ridge Regression**
3. **Lasso Regression**
4. **Decision Tree Regressor**
5. **Random Forest Regressor**

## 📊 Performance Metrics

Models are evaluated using:
- **R² Score**: Measures how well the model explains variance
- **Mean Absolute Error (MAE)**: Average absolute difference between predicted and actual values
- **Root Mean Squared Error (RMSE)**: Square root of average squared differences

## 📝 Dataset Features

- **Model**: Laptop brand and model name
- **Star Rating**: Average customer rating
- **Number of Ratings**: Total ratings count
- **Number of Reviews**: Total reviews count
- **Processor**: CPU specifications
- **RAM**: Memory size
- **OS**: Operating system
- **Storage**: Storage capacity and type
- **Size**: Screen size
- **Price**: Target variable (in ₹)

## 🔍 Key Insights

- Detailed insights will be generated after running the analysis
- Feature importance visualization shows which specifications most impact price
- Correlation analysis reveals relationships between features

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👥 Authors

**Group 4**
- Project developed as part of Big Data Analytics coursework

## 🙏 Acknowledgments

- Data sourced from Flipkart
- Built using open-source libraries
- Thanks to the Python data science community

## 📧 Contact

For questions or feedback, please open an issue in the repository.

---

⭐ If you found this project helpful, please consider giving it a star!
