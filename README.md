# webscraping challenge

This challenge involves two technical products as deliverables:  

Deliverable 1: Scrape titles and preview text from Mars news articles.  

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table. 


## Acknowledgements

The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.


## Part 1: Scrape Titles and Preview Text from Mars News

- Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).

- The titles and preview text of the news articles were scraped and extracted. 

- The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries, articles_info.


## Part 1: Scrape and Analyze Mars Weather Data

- The HTML table was extracted into a Pandas DataFrame, mars_temp_df. Beautiful Soup was used to scrape the data. The columns were given the required headings and data types.

The data was analyzed to answer the following questions:  

- How many months exist on Mars? 
- How many Martian days' worth of data are there? 

The data was analyzed to answer the following questions, and a data visualization was created to support each answer:  

- Which month, on average, has the lowest temperature? The highest?  

- Which month, on average, has the lowest atmospheric pressure? The highest?
- How many terrestrial days exist in a Martian year? A visual estimate was made.

- The DataFrame was exported into a CSV file, mars_temp.csv.