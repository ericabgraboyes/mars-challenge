# mars-challenge

## Background
The assignment consists of two technical products:
    
    Deliverable 1: Scape titles and preview text from Mars news articles
        * use automated browsing to visit the mars news site
        * create a beautiful soup object to extract article title and summary
        * store each title and preview pair in a Python dictionary. Title and preview are both keys. Store all dictionaries in a python list
        * export to csv file
    
    Deliverable 2: Scrape and analyze mars weather data which exists in the table
        * use automated browsing to visit the mars table
        * create a beautiful soup object to scrape the table -- header and all rows
        * assemble scraped table into a Pandas DF -- the column names should match the website table
        * analyze the data type on the columns and convert as necessary for analysis purposes
        * use the dataframe to analyze following questions:
            * How many months exist on Mars?
            * How many Martian days worth of data exist in the scraped dataset
            * What are the coldest and warmest months? Plot results as a bar chart
            * Which months have the lowest and highest atmospheric pressure? Plot results as a barchart
            * How many earth days exist in a Martian year?  Answer should include graphical plot