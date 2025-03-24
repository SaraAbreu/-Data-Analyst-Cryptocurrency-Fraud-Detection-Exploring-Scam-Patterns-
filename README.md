# -Data-Analyst-Cryptocurrency-Fraud-Detection-Exploring-Scam-Patterns-
This project explores the analysis of cryptocurrency scams using a publicly available dataset. Given the growth and constant presence of cryptocurrencies in the digital world, I decided to investigate fraud patterns in this area. Throughout this analysis, I have worked with data on scam URLs, fraud categories, platforms involved, and connection networks between scammers. The aim is to provide a deeper understanding of the tactics used by scammers and how these scams can be identified and prevented.

You can see the analysis of kaggle at https://www.kaggle.com/code/saraabreuhernandez/an-lisis-de-estafas-de-criptomonedas

For this analysis, the primary programming language used was Python. Python is widely used for data analysis due to its extensive libraries and tools for data manipulation, visualization, and statistical analysis. Specifically, the following libraries were used:

Pandas – For data manipulation and handling datasets (e.g., loading CSV files, cleaning data, and performing analysis).

Matplotlib and Seaborn – For data visualization, including creating bar charts, histograms, and network graphs.

Numpy – For handling arrays and mathematical functions.

Urllib.parse – For extracting domains from URLs.

NetworkX – For creating network graphs to analyze connections between scammers.

Motivation: Cryptocurrencies, while offering investment and development opportunities, are also fertile ground for fraudsters. This project was born out of my interest in better understanding how these frauds are perpetrated and how victims are lured. By analyzing these types of frauds, one can contribute to a safer digital environment and help raise awareness of the risks associated with cryptocurrencies.

# Cryptocurrency Scam Analysis Procedure
This analysis was carried out using a publicly available dataset on cryptocurrency scams. The main objective was to identify patterns and trends in cryptocurrency fraud, as well as understand the tactics used by scammers. Below are the key steps of the procedure:

### 1. Data Loading and Preprocessing

* Dataset loading: The urls.csv and uris.csv files from the Kaggle dataset were downloaded and loaded.

* Initial exploration: Preliminary checks were performed to understand the data structure, identify missing values, and get an overview of the columns of interest, such as scam URLs, categories, subcategories, and wallet addresses.

* Data cleaning: During exploration, rows with missing values were removed, and columns were transformed to facilitate further analysis. For example, domains were extracted from the URLs to identify the platforms most involved in the scams.

### 2. Analysis of Scam URLs
Domain extraction: Domains were extracted from the URLs present in the urls.csv file using Python's urlparse library.

Identification of most common platforms: The most frequently involved platforms in cryptocurrency scams were counted. It was observed that sites like medium.com and telegram.ph were commonly used by scammers.

Visualization: Bar charts were generated to represent the most used platforms and make the results easier to interpret.

### 3. Analysis of Scam Categories and Subcategories

* Category analysis: The category column was examined to identify the most common scam categories, such as scamming, phishing, and fake ICO.

* Subcategory analysis: The subcategories within each scam type were explored, revealing that the trust-trading subcategory was common in scamming scams, while myetherwallet and OmiseGO stood out in the phishing and fake ICO categories, respectively.

### 4. Analysis of Platforms and Reporters

* Most involved platforms: The relationship between the platforms involved in scams and the reporters who reported them was analyzed, highlighting that CryptoScamDB was the most commonly associated reporter with these types of fraud.

* Scammer network connections: Network graphs were built to visualize the connections between different actors in the scams. It was observed that CryptoScamDB and twitter.com were connected in the scammer networks.

### 5. Analysis of Scam Descriptions

* Key words: A text analysis was performed to identify the most common words in scam descriptions. Terms like trading, trust, 1eth, 2eth, and 5eth stood out, suggesting recurring patterns in scams focused on investments and promises of high returns.

### 6. Conclusions and Findings

* Identified trends: The analysis revealed that cryptocurrency scams are heavily associated with platforms like telegram.com and medium.com, with the most common categories being scamming, phishing, and fake ICO.

* Scammer tactics: Scammers were found to use tactics such as trust-trading and impersonating popular sites like myetherwallet.

* Common vulnerabilities: The most common vulnerabilities include users' trust in investment platforms without proper verification and the use of promises of quick returns.

### 7. Prevention Recommendations
* Throughout the analysis, the importance of maintaining education on cryptocurrency scams and how users can protect themselves was emphasized. Additionally, the implementation of more robust tools to detect fraud patterns and improve cooperation between platforms, regulators, and users was suggested.
