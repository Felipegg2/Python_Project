# **Python_Project: Web-Scraping with Python**

This repository contains a web scraping project that collects data from [List of largest companies in Canada](https://en.wikipedia.org/wiki/List_of_largest_companies_in_Canada). The primary focus of this project is to create and export a CSV file based on the information available on a web page and generate informative charts using Python and its libraries.

## 👨‍💻 **Author: [Felipe Gonzalez](https://www.linkedin.com/in/felipegzgc/)**

## 📖 **About the Project**
The objective of this project is to scrape data from a website. To analyze some legal implications. To generate insightful charts, and save the results in CSV files for further analysis. It is essential to respect the legal constraints and terms of service of the websites being scraped to ensure ethical and responsible data collection.

## 🧑‍⚖️ **Legal Impacts**
When conducting web scraping, it is crucial to consider the legal implications and adhere to ethical guidelines. Make sure to:

- Review the terms of service and robots.txt file of the websites you are scraping.
- Respect any copyrights, trademarks, or intellectual property rights.
- Avoid overloading the target website with requests to prevent denial of service.
- Always ensure that your web scraping activities comply with relevant laws and regulations in your jurisdiction.

## ▶️ **Getting Started**
To get started with this project, follow these steps:

## ℹ️ **Data Analysis**
The collected data is analyzed to generate insightful charts and visualizations. Data analysis tools and techniques used in this project include:

- Visualization using different libraries: Pandas, BeatifulSoup, Matplotlib, Numpy and Seaborn.
- Data cleaning and preprocessing.


## 🎯 **Results**
The results of the web scraping and data analysis are presented in the following:

### 📑 [Google Colaboratory Notebook:](https://colab.research.google.com/drive/1SGULtSjdpXjII-JdNGPaSjBJWXcehxa1?usp=drive_link) 

This colaboratory notebook contains all the Python code necessary to develop this project, including how web scraping was achieved and the step-by-step guide to creating the database in CSV file.

Following you can see the titles and dataframe's head developed.

    df = pd.DataFrame(columns=table_titles)
    df

![image](https://github.com/Felipegg2/Python_Project/assets/147356131/48d6c69e-f084-4eff-b9b3-a4f93a80f2ca)


    df.head()

![image](https://github.com/Felipegg2/Python_Project/assets/147356131/a8e9304f-aedd-4ca6-aa32-edc6b126ebe4)



For analysis and data visualization it was necessary changed some values from string to float type. It was used the function *df['columnx'] = pd.to_numeric(df['columnx'], errors='coerce')*. It is important to advice that this function has a little problem reconizing the negatives numbers, it replaces that kind of number by noyhing (Nan), you must take care with this changes.



### 💾 [*CSV file:*](https://github.com/Felipegg2/Python_Project/blob/main/largest%20companies%20in%20Canada.csv) "largest companies in Canada.csv" 

Named "largest companies in Canada.csv", that CSV file was generated through web scraping in this repository. It contains the data that was gotten from the table of web page: titles and data of each row. 




or, you might check the code on this [URL](https://github.com/Felipegg2/Python_Project/blob/main/python_project.ipynb)

## 🔢 Four charts developed with Matplotlib:

   ### 📊 Bar Chart: Shows the top 10 companies with the highest revenue.

![image](https://github.com/Felipegg2/Python_Project/assets/147356131/1db7fff3-1473-47ba-8dd3-9d581c15f707)

   ### 📈 Scatter plot: Illustrates the correlation between companies' values and their profits, aiming to explain if higher-value companies have better profits.

![image](https://github.com/Felipegg2/Python_Project/assets/147356131/296c9438-5a2b-4ab9-9152-29c32bc5c03d)

   ### 💰 Histogram chart:  Displays the distribution of profits, revealing that more than 30 companies have profits lower than 2 billion US dollars.

![image](https://github.com/Felipegg2/Python_Project/assets/147356131/213fba1f-35bd-409b-ae3f-a73b60d08b00)

   ### 📏 Box splot: Represents the distribution of company assets. X-axis is represents in billion US dollars.
   
![image](https://github.com/Felipegg2/Python_Project/assets/147356131/748797db-abaa-42a9-89da-4f846f08ef83)


## **Contributing**
Contributions to this project are welcome. If you have ideas for improvements, bug fixes, or additional features, feel free to open an issue or submit a pull request.

Enjoy exploring, analyzing, and responsibly scraping data with this project! If you have any questions or need further assistance, please don't hesitate to reach out.
