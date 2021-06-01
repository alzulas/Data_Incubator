# Data_Incubator
Capstone for the Data Science Incubator

The main code for this if the WIkipedia.ipynb notebook. 
It includes all of the code that I wrote to scrape data and running the models for NLP as well as new scrapings for selecting new items that meet the requirements of "likely to be reverted".
It's a little disorganized, so I tried to write a second notebook that just grabbed the new items using the model from the first notebook, that's daily_auto_scraper.ipynb.
That didn't end up being the thing that ran the final results though.

This github does NOT include the full training data. It's way too big. That can be found at https://www.kaggle.com/alzulas/wikipedia-controversial-pages-change-history

#Future to dos:
1. Clean up original codebase
2. Make the daily runner work properly
3. Build a model to determine whats the likely reason for the revert - add this information to the daily runner
4. Allow for pagination of the website page
5. Create a pipeline that runs the model in the mornings, and populates the csv to send to the webpage
