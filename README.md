## Scraping of journals on renewable energy, sustainability, and environment

Notebook link : https://jovian.com/prabhakarrawat/webscraping-project

## Introduction
While working at Vizag Steel as an industrial engineer I got first-hand experience on the polluting impact of the steel and power industry. I designed simulations and wrote programs to reduce the plant’s overall carbon emissions. What stuck with me is that the steel industry contributes 3 Tons of CO2 for the production of 1 Ton of Crude steel. On the contrary, I am excited by the potential of the same CO2 emissions to be ‘electrolyzed’ into fuels, and petrochemicals instead. Eventually this process is reducing CO2 emissions in environment, thus making our environment better. So, I have decided to scrape the ranking of journals in the field of renewable energy, sustainability and environment.

Web scraping is process of extracting information or data in structured form from website, which is generally written is HTML(Hyper Text Markup Language) and is in unstructured form. Web scraping can be done manually, or by using bots or by using an automated program. Some of applications of web scrapining includes price analysis, market research and sentiment analysis. Here we are scraping the data using python and it's inbult libraray and some of external libraries. For more infomation on web scrapping click here.

Steps followed in this project:
1. Download the web page using requests library
2. Parse the HTML source code using beautifulsoup4 get journal title, journal url, SJR Index, H Index and country
3. Extract the required information from page
4. Compile extracted information into python list
5. Save the extracted information to a csv file
