# 🔐 MPIN Strength Analyzer

A Streamlit web application that analyzes the strength of your Mobile PIN (MPIN) by checking for common patterns and personal date vulnerabilities.

![App Screenshot](https://i.imgur.com/JQ8W0xU.png)  
*Live Demo: [MPIN Analyzer on Streamlit](https://mpinanalyser-5xg7t8b5x6n3tkqphuohsd.streamlit.app/)*

## 🌟 Features

- **PIN Strength Analysis**: Evaluates 4-digit and 6-digit MPINs
- **Common Pattern Detection**: Checks against lists of commonly used weak PINs
- **Personal Date Analysis**: Identifies vulnerabilities from:
  - Your birth date
  - Spouse's birth date
  - Wedding anniversary
- **Comprehensive Testing**: Built-in test suite with 21 test cases
- **Visual Feedback**: Clear strength indicators and recommendations

## 🚀 How It Works

1. **Select PIN Length**: Choose between 4-digit or 6-digit MPIN
2. **Enter Your MPIN**: Input your PIN (secured with password masking)
3. **Optional Personal Info**: Add dates for more accurate analysis
4. **Get Analysis**: View strength rating and specific vulnerabilities

## 🛠️ Technical Implementation

### Detection Methods
- **Common PINs**: Checks against predefined lists of vulnerable PINs
- **Date Patterns**: Detects various date formats (DDMM, MMDD, YYMMDD, etc.)
- **Sequential/Repeating Numbers**: Identifies simple patterns

### Code Structure
mpin-analyzer/
├── app.py # Main Streamlit application
├── README.md # This documentation
├── requirements.txt # Python dependencies


### Technologies Used
- Python 3.9+
- Streamlit (Web framework)
- Pandas (Test results display)
- Python datetime (Date pattern extraction)

## 📊 Test Suite

The application includes a comprehensive test suite that verifies:
- Common PIN detection
- Date pattern matching
- Edge case handling
- Invalid input detection

![Test Suite Screenshot](https://i.imgur.com/5XJQqLp.png)

## 🏗️ Project Setup

### Prerequisites
- Python 3.9+
- pip package manager

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mpin-analyzer.git
   cd mpin-analyzer
   ```
2. Install dependencies:

```bash
pip install -r requirements.txt
```
3.Run the application:

```bash
streamlit run app.py
```
## 🌐 Deployment
The app is deployed on Streamlit Community Cloud. To deploy your own version:

Create a Streamlit account

Connect your GitHub repository

Configure deployment settings

Deploy!

## 📝 Usage Guidelines
Never enter your real banking MPIN

For demonstration purposes only

Use generated or test PINs for analysis

## 📧 Contact
For questions or suggestions, please contact:
aryansethiya111@gmail.com
