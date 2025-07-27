# IPL Teams Data Analysis 🏏

A comprehensive web scraping and data visualization project analyzing Indian Premier League (IPL) teams' financial and squad information.

## 📊 Project Overview

This project consists of two main components:
1. **Web Scraping**: Extracting IPL teams data from web sources
2. **Data Visualization**: Creating interactive charts and dashboards using the scraped data

## 🚀 Features

### Web Scraping Module
- Scrapes IPL team information including:
  - Team names and serial numbers
  - Remaining funds/budget
  - Total players count
  - Overseas players count
- Handles dynamic web content with BeautifulSoup
- Robust error handling for missing elements
- Data cleaning and preprocessing
- Exports clean data to CSV format

### Data Visualization Module
- Creates comprehensive dashboards with multiple chart types:
  - Bar charts for funds analysis
  - Pie charts for player distribution
  - Stacked bar charts for composition analysis
  - Line plots for trend analysis
- Automatic column detection and mapping
- Responsive design with proper text sizing
- Professional styling with color schemes
- Summary statistics and insights

## 🛠️ Installation

### Prerequisites
```bash
# Required Python packages
pip install pandas
pip install matplotlib
pip install seaborn
pip install beautifulsoup4
pip install requests
pip install numpy
```


## 📁 Project Structure

```
ipl-teams-analysis/
│
├── scraping/
│   ├── ipl_scraper.py          # Main scraping script
│   └── requirements.txt        # Scraping dependencies
│
├── visualization/
│   ├── data_visualizer.py      # Main visualization script
│   └── requirements.txt        # Visualization dependencies
│
├── data/
│   ├── raw_data.csv           # Raw scraped data
│   └── cleaned_data.csv       # Processed data
│
├── images/
│   ├── dashboard_sample.png   # Sample dashboard output
│   └── charts_preview.png     # Individual charts preview
│
├── README.md
└── LICENSE
```

## 🔧 Usage

### 1. Web Scraping

```python
# Run the web scraper
python scraping/ipl_scraper.py

# The script will:
# - Extract data from the target website
# - Clean and process the information
# - Save results to CSV file
# - Display summary statistics
```

**Key Features of Scraper:**
- Handles missing HTML elements gracefully
- Multiple fallback strategies for data extraction
- Automatic duplicate removal
- Text cleaning and formatting

### 2. Data Visualization


**Generated Visualizations:**
1. **Funds Analysis** - Team-wise budget remaining
2. **Player Distribution** - Squad composition across teams
3. **Correlation Analysis** - Relationship between funds and squad size
4. **Performance Metrics** - Multi-dimensional team comparison
5. **Trend Analysis** - Data patterns and insights

## 📈 Sample Output

### Key Insights Generated:
- Teams with highest/lowest remaining funds
- Average squad sizes across teams
- Overseas vs domestic player ratios
- Financial performance rankings
- Squad composition patterns

## 🔍 Data Sources

The scraper targets IPL team information from official sources, extracting:
- **Team Names**: All 10 IPL franchise teams
- **Financial Data**: Remaining auction budgets
- **Squad Information**: Player counts and compositions
- **Performance Metrics**: Various team statistics


## 🚨 Error Handling

The project includes comprehensive error handling:

### Scraping Errors
- **AttributeError**: Handles missing HTML elements
- **Connection Issues**: Retry mechanisms for network problems
- **Data Format Issues**: Automatic data type conversion

### Visualization Errors
- **Missing Columns**: Automatic column detection and mapping
- **Data Type Issues**: Flexible data preprocessing
- **Display Problems**: Responsive text sizing and layout

## 📊 Technical Details

### Web Scraping Technology Stack
- **BeautifulSoup4**: HTML parsing and extraction
- **Requests**: HTTP requests and web content fetching
- **Pandas**: Data manipulation and CSV operations
- **Regex**: Text cleaning and pattern matching

### Visualization Technology Stack
- **Matplotlib**: Core plotting and chart generation
- **Seaborn**: Statistical visualization and styling
- **NumPy**: Numerical computations and data processing
- **Pandas**: Data analysis and manipulation


### Contribution Guidelines
- Follow PEP 8 Python style guide
- Add comments for complex logic
- Include error handling for new features
- Update documentation for API changes
- Add unit tests for new functions


## 🙏 Acknowledgments

- IPL official sources for data availability
- BeautifulSoup4 community for excellent documentation
- Matplotlib/Seaborn teams for visualization capabilities
- Python community for continuous support

## 📈 Future Enhancements

- [ ] Real-time data updates
- [ ] Interactive web dashboard
- [ ] Machine learning predictions
- [ ] Historical data analysis
- [ ] Mobile app integration
- [ ] API development for data access
- [ ] Advanced statistical analysis
- [ ] Player performance metrics

---

**⭐ Star this repository if you found it helpful!**

---

*Last updated: July 2025*
