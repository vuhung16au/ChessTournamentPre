# What is This Tool?

This tool help you gather data for chess players in a single place, 
making it easier to prepare for tournaments and research potential opponents. 

Some use cases 
1. Regularly play at your local club, city? Track and research your frequent opponents.
2. Prepare for your next tournament? Identify your potential opponents and analyze their most played openings.

# How to Run 

```bash 
$python3 -m venv .myenv
$. .myenv/bin/activate
(.myenv)$pip install -r requirements.txt 
$python app.py
``` 

open `http://localhost:5430/`

# Tournament Prep in Action 

## Player list 
![alt text](image-1.png)

## Add a new player 
![alt text](image-2.png)

# Note on fide-ratings-scraper

`fide-ratings-scraper` is a npm package the helps fetching FIDE info from the server. 

Installation: `npm i -g fide-ratings-scraper`
Get player info: `fide-ratings-scraper get <FideID>`
