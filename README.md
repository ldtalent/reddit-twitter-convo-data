# Reddit Conversation Data Scraping using BeautifulSoup & Colaboratory

Simple tools to scrape Reddit while maintaining all of their contextual data, such as the convrsational tree, vote count, subreddit, username, etc. Utilizing Colaboratory & Google Drive both to save computational resources & space, easily integrated for further usage such as machine learning, data analyzing, etc.

Complete explanation can be found through the notebook. Meanwhile detailed explanation is provided in the [LearningDollars blog](https://blog.learningdollars.com/?p=2185).

## Setup

No special setup needed as the whole process done in Colaboratory. For local usage, you may clone the repository & run it as if you run any other Python Notebook.

## Options

The main options are the ones provided in the hyperparameters block.

- `PAGES` - Number of pages from each subreddit to be scraped.
- `SUBREDDIT` - List of subreddit.
- `SORT` - Sorting type, set to hot, new, rising, controversial, top, or gilded.
- `TIME` - Sorting timespan, set to hour, week, month, year, or all.