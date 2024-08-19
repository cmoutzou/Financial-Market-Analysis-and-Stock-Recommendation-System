# **Financial Market Analysis and Stock Recommendation System**

## **Description**
This project offers a thorough analysis of selected stocks by integrating various financial indicators, macroeconomic data, and sentiment analysis on related news. The system gathers data from Yahoo Finance, Alpha Vantage, and the Federal Reserve Economic Data (FRED) API to generate stock recommendations.

## **Features**
- **Stock Data Fetching:** Retrieves stock data from Yahoo Finance and Alpha Vantage.
- **Macroeconomic Analysis:** Analyzes GDP, inflation, unemployment rate, interest rates, consumer confidence, and PMI.
- **Technical Indicators:** Calculates key technical indicators like Moving Averages (MA), Relative Strength Index (RSI), MACD, Bollinger Bands, and Average True Range (ATR).
- **News Sentiment Analysis:** Performs sentiment analysis on stock-related news using TextBlob.
- **Stock Recommendations:** Provides buy, sell, or hold recommendations based on a combination of technical, macroeconomic, and sentiment analysis.
- **Interactive Charts:** Generates dynamic and interactive charts for each stock symbol, displaying price movements, technical indicators, and sentiment scores. Users can explore different timeframes, zoom in on specific data points, and analyze the performance of the stocks visually.

## **Installation**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   ```
2. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up API keys:**
   - Replace `"your_alpha_vantage_api_key"` and `"your_fred_api_key"` in the script with your actual API keys.

## **Usage**
1. **Run the main script** to process the selected symbols (e.g., AAPL, NVDA, TSLA) and receive analysis, recommendations, and interactive visualizations:
   ```bash
   python main.py
   ```
2. **Explore the Output:**
   - The script will output the macroeconomic analysis, sentiment analysis, and stock recommendations.
   - **Visual Charts:** Review interactive charts that display stock data with technical indicators. The charts allow you to:
     - Zoom in and out on specific timeframes.
     - Toggle different indicators on and off.
     - Analyze the stock's performance with integrated sentiment and macroeconomic data.

## **Example Output**
The output includes:
- **Financial Analysis Sentiment:** Positive/Negative/Neutral
- **Macroeconomic Analysis Sentiment:** Positive/Negative/Neutral
- **News Sensitivity Analysis Sentiment:** Positive/Negative/Neutral
- **Interactive Charts:** Dynamic visual representation of stock data with technical indicators, allowing for detailed analysis and exploration.

## **Contributing**
Feel free to fork this repository, make enhancements, and submit a pull request. Contributions are welcome!

## **License**
This project is licensed under the MIT License. See the LICENSE file for more details.

## **Contact**
For any questions or inquiries, please contact [christosmoutzouris@gmail.com](mailto:christosmoutzouris@gmail.com).

---

This version emphasizes the charting functionalities, making it clear that potential employers can interact with and explore the generated visualizations.
