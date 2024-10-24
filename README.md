# Currency Converter

## Overview
This Currency Converter is a desktop application built using Python's `tkinter` library. It allows users to convert a specified amount between two different currencies using live exchange rates. The application fetches data from the RapidAPI currency conversion API to ensure real-time currency values.

## Features
- **Simple and User-Friendly Interface**: The application features an intuitive graphical interface where users can easily input their values and select currencies for conversion.
- **Live Currency Conversion**: It fetches live currency rates from an external API to ensure accurate conversions.
- **Multiple Currencies**: Supports a variety of commonly used currencies like CAD, INR, EUR, USD, GBP, and PKR.
- **Instant Results**: Provides real-time results upon entering the amount and clicking the "CONVERT" button.
- **Formatted Output**: Displays the converted currency in a user-friendly format (e.g., `1,234.56`).

## Future Enhancements
- **Expanded Currency Support**: Add more currencies to support a wider range of international conversions.
- **Historical Data**: Provide an option to view historical exchange rates for better analysis.
- **Offline Mode**: Enable offline functionality by caching recent exchange rates.
- **Currency Trends**: Incorporate a graph or chart to show trends for specific currency pairs over time.
- **Mobile Integration**: Develop mobile versions of the application for both iOS and Android.

## Usage
### Prerequisites
1. **Python**: Ensure that you have Python 3.x installed on your system.
2. **Required Libraries**: Install `tkinter`, `requests`, and `json` (if not pre-installed). You can install them using the following commands:
   ```bash
   pip install tkinter requests
   ```

### Instructions
1. Clone the repository or download the script.
2. Open the terminal or command prompt in the folder where the script is located.
3. Run the Python file:
   ```bash
   python currency_converter.py
   ```
4. Enter the amount to be converted in the input field.
5. Select the currency you want to convert from and to using the dropdown menus.
6. Click the "CONVERT" button to get the converted amount.

### Example
- Convert 100 USD to EUR:
   - Input: 100
   - From: USD
   - To: EUR
   - Output: A formatted result showing the converted value.

## API Integration
This application uses the RapidAPI Currency Converter API for real-time data. You will need to obtain your own API key and replace the provided API key in the script.

```python
headers = {
    "x-rapidapi-key": "YOUR_API_KEY_HERE",
    "x-rapidapi-host": "currency-converter18.p.rapidapi.com"
}
```

Ensure that you have a valid API key before using the application.

## Conclusion
This Currency Converter is a helpful tool for anyone needing quick currency conversions with accurate and live data. The ease of use, along with the potential for future enhancements, makes it suitable for both personal and professional use cases.
