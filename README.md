# 🏆 AI Investment Estimations - Gold Assistant

A comprehensive AI assistant for gold investment analysis featuring multiple specialized agents, real-time price data, and multi-language support.

## 🌟 Features

### Multiple AI Agents
- **Gold Price Agent**: Fetches real-time gold prices from MetalpriceAPI
- **Investment Advisor Agent**: Provides timing recommendations based on market conditions
- **Purchase Simulation Agent**: Records fake gold purchases to JSON file
- **Translation Agent**: Translates all responses to Arabic using OpenAI
- **Speech-to-Text Agent**: Converts voice input to text using OpenAI Whisper

### Multi-Panel Interface
- **Left Panel**: English chat with text and voice input
- **Right Panel**: Real-time Arabic translations
- **Bottom Panel**: Feature descriptions and supported currencies

### Supported Countries/Currencies
USA (USD), UK (GBP), Europe (EUR), Japan (JPY), Canada (CAD), Australia (AUD), India (INR), China (CNY), Saudi Arabia (SAR), UAE (AED), Egypt (EGP)

## 🚀 Quick Start

### 1. Install Dependencies
```bash
pip install -r requirements_ai_investment.txt
```

### 2. Set Up API Keys
Create a `.env` file in the week2 directory with:
```env
OPENAI_API_KEY=your_openai_api_key_here
METAL_PRICE_API_KEY=your_metal_price_api_key_here
```

#### Getting API Keys:
- **OpenAI API Key**: Sign up at [OpenAI](https://platform.openai.com/)
- **Metal Price API Key**: Sign up at [MetalpriceAPI](https://metalpriceapi.com/) (free tier available)

### 3. Run the Assistant
Open `ai_investment_estimations.ipynb` in Jupyter Lab and run all cells.

### 4. Test Your Setup
Run the demo test script first:
```bash
python demo_test.py
```
