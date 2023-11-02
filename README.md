# **Python_Project: Web-Scraping with Python**

This repository contains a web scraping project that collects data from [List of largest companies in Canada](https://en.wikipedia.org/wiki/List_of_largest_companies_in_Canada), specifically from the table titled **_2019 Forbes list_**. The primary goal of this project is to create a dataframe in a Google Colaboratory notebook, export the available information to a CSV file, and generate useful graphical charts using Python and its libraries.


# 👨‍💻 **Author: [Felipe Gonzalez](https://www.linkedin.com/in/felipegzgc/)**


## 📖 **About the Project**
The objective of this project is to scrape data from a website. To analyze some legal implications. To generate insightful charts, and save the results in CSV files for further analysis. It is essential to respect the legal constraints and terms of service of the websites being scraped to ensure ethical and responsible data collection.


## 🧑‍⚖️ **Legal Impacts**
When conducting web scraping, it is crucial to consider the legal implications and adhere to ethical guidelines. Make sure to:

- Review the terms of service and robots.txt file of the websites you are scraping.
- Respect any copyrights, trademarks, or intellectual property rights.
- Avoid overloading the target website with requests to prevent denial of service.
- Always ensure that your web scraping activities comply with relevant laws and regulations in your jurisdiction.


## ℹ️ **Data Analysis**

The collected data is analyzed to generate a CSV file and create insightful charts and visualizations. The data analysis tools and techniques used in this project include:

- Utilizing Python code to extract information directly from websites.
- Employing libraries such as **Pandas, BeautifulSoup, Matplotlib, NumPy, and Seaborn.**
- Developing data visualizations using the **Matplotlib** library.
- Preprocessing certain columns before graphing by **converting string data types to float types**.
- Maintaining the original information in CSV file without any alterations or modifications to the URL.


## 🎯 **Results**
The results of the web scraping and data analysis are presented in the following:

_Note: you might access deliverables through links in each case._

### 📑 [Google Colaboratory Notebook:](https://colab.research.google.com/drive/1SGULtSjdpXjII-JdNGPaSjBJWXcehxa1?usp=drive_link) 

This Google Colaboratory notebook contains all the Python code necessary to develop this project. It includes how web scraping was achieved and the step-by-step guide to creating the database in CSV file.

Below you can check the titles and dataframe's head developed.

- Titles:
    df = pd.DataFrame(columns=table_titles)
    df

![image](https://github.com/Felipegg2/Python_Project/assets/147356131/48d6c69e-f084-4eff-b9b3-a4f93a80f2ca)

- Dataframe's head:
    df.head()

![image](https://github.com/Felipegg2/Python_Project/assets/147356131/a8e9304f-aedd-4ca6-aa32-edc6b126ebe4)


To facilitate analysis and data visualization, it was necessary to convert certain string values to float types. The function used for this purpose is df['columnxx'] = pd.to_numeric(df['columnxx'], errors='coerce'). However, it's important to note that this function may have a slight issue recognizing negative numbers, as it replaces them with 'NaN.' Therefore, it's advisable to exercise caution when dealing with these changes.

### 💾 [*CSV file:*](https://github.com/Felipegg2/Python_Project/blob/main/largest%20companies%20in%20Canada.csv) "largest companies in Canada.csv" 

It is called "largest companies in Canada.csv", that CSV file was generated through web scraping in this repository. It contains the data that was gotten from the table of the web page: titles and data of each row. It has 9 columns and 57 rows, including titles' row.


## 🔢 Data Visualization:

Four charts were created using the Matplotlib library. These charts aim to illustrate various descriptive measurements, such as the top 10 companies with the highest revenues, the distribution of profits, and the distribution of assets. Additionally, a scatter plot is used to demonstrate the relationship between the companies' values and the profits achieved within Canadian companies.

   ### 📊 Bar Chart: Shows the top 10 companies considering their revenue accurate.

The companies are not sorted by revenue but rather in accordance with Forbes' 2000 rank:

5 out of 10 are involved in banking **(Royal Bank of Canada, Toronto-Dominion Bank, Scotiabank, Bank of Montreal, Canadian Imperial Bank of Commerce)**.

2 out of 10 operate in the insurance sector **(Manulife, Sun Life Financial)**.

Another 2 out of 10 are in the oil and gas industry **(Enbridge, Suncor Energy)**.

Finally, **Brookfield Asset Management** is categorized under the finance sector.


![image](https://github.com/Felipegg2/Python_Project/assets/147356131/1db7fff3-1473-47ba-8dd3-9d581c15f707)


   ### 📈 Scatter plot: Illustrates the correlation between companies' values and their profits.

The correlation between these variables was 0.865, signifying a strong positive relationship between the data in both of them. Therefore, it can be inferred that as a company's value increases, its profits are more likely to increase as well.
   

![image](https://github.com/Felipegg2/Python_Project/assets/147356131/65c18713-58aa-4f45-8042-b8e4acf64a71)


   ### 💰 Histogram chart:  Displays the distribution of profits.
   
It is notable that more than 35 companies have profits lower than 2 billion US dollars, while only 5 companies have exceeded the 5 billion USD threshold.

![image](https://github.com/Felipegg2/Python_Project/assets/147356131/213fba1f-35bd-409b-ae3f-a73b60d08b00)

   ### 📏 Box splot: Represents the distribution of company's assets. 

The majority of companies have assets totaling less than 100 billion US dollars, although there are at least 10 companies with assets higher than 100 billion USD. 

Analyzing the chart alone, we can observe that the first quartile (Q1) is notably low, at approximately 20 billion USD or less. The median is positioned below 50 billion USD, while the upper quartile (Q3) is approximately around 50 billion USD.

The X-axis is represented in billion USD.

![image](https://github.com/Felipegg2/Python_Project/assets/147356131/748797db-abaa-42a9-89da-4f846f08ef83)


## **Contributing**
Contributions to this project are welcome. If you have ideas for improvements or additional features, feel free to open an issue or submit a pull request.

Enjoy exploring, analyzing, and responsibly scraping data with your projects!



## **Deep gratitude to [Cantek Canada](https://www.cantekcanada.com/) and its instructor, Will Edwards, for all supports and guiance in our path in data analysis.**





