This is an Article sumarizer built with Hugging face text summarizer pipeline and python beautiful soup
The article was requested using the python request module and then scraped using beautiful Soup. 
The article was first cut into chunks so as to stay within the hugging face parameters
Then the chunks were then summarized using the  hugging face text summarization pipeline.
The summarized chunks were then added back together into one body using the python .join() statement.
The summarized text was then saved to a .txt file.
