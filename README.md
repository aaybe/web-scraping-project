# web-scraping-project
Quote guessing game. This program scrapes "quotes.toscrape.com" for quotes and stores them on a CSV file, which is then called every time the user starts the program to make a quote author guessing game.

- Demo of game: https://www.youtube.com/watch?v=fg8eqIZiLuE

To run clone repository. quote-scraper.py starts the game. BeautifulSoup will need to be installed:
- $ pip install beautifulsoup4 

The program chooses a random quote from https://quotes.toscrape.com/ and displays it to the user. User then has 4 tries to correctly write the name of the author. After each failed try, the user is given a new hint.
1. User is given date and place of birth of author
2. User is given author's first name initial
3. User is given author's last name initial


After the game ends, the user is asked if they want to run again.
