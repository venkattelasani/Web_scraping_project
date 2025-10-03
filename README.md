# Web_scraping_project
**Analyzing Factors Affecting Earbud Prices on Flipkart**

## 📌 Problem Statement
The project aims to analyze how various features influence the selling price of earbuds on Flipkart and provide actionable insights for both consumers and businesses.

## 🎯 Objective
- Identify key features impacting earbud prices.  
- Understand brand dominance and market presence.  
- Provide insights for sellers and consumers to make data-driven decisions.

## 📊 Dataset & Features
**Source:** Flipkart (Web Scraping)  

**Target Variable:** `Selling Price`  

**Independent Variables:**
- `Product_Name`  
- `Brand`  
- `Battery_Life_in_HRS`  
- `Drivers`  
- `Microphone_ENC`  
- `Additional_Features`  
- `Discount%`  
- `Rating`  

## 🛠️ Methodology

### 1. Web Scraping
- **Website:** Flipkart TWS Search  
- **Tools:** `Requests`, `BeautifulSoup`  

### 2. Data Cleaning
- Removed null values and duplicates  
- Modified data types for consistency  
- Extracted features into a structured DataFrame  

### 3. Exploratory Data Analysis (EDA)
- Analyzed distribution of brands, features, and prices  
- Identified correlations between product features and selling price  
- Visualized data using plots and charts  

## 📈 Key Insights

### Brand Dominance
- **Boult** has the highest product count (~2040), making it the most dominant brand on Flipkart.

### Pricing Trends
- High-end brands like **Sony, PTron, Hectic** average around ₹2000  
- Budget-friendly brands like **Aroma, Boult** average ₹700–₹900  

### Feature Impact
- ANC (Active Noise Cancellation) and ENC (Environmental Noise Cancellation) significantly increase prices  
- **Boult** shows the widest price range (₹700 – ₹7990)  

### Ratings Influence
- Customer ratings moderately affect pricing  

### Connectivity
- Wireless earbuds generally cost more than wired ones  

## 💡 Business Implications
- **For Sellers:** Highlight premium features like ANC/ENC to justify higher prices  
- **For Competitors:** Differentiate via unique features and competitive pricing  
- **For Consumers:** Consider Boult for affordable yet varied options, or premium brands for advanced features  

## 🔮 Future Scope
- Expand dataset across multiple e-commerce platforms  
- Build a price prediction model using Machine Learning  
- Develop a real-time dashboard for dynamic price tracking  

## 📂 Repository Structure
