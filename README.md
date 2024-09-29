# What is This Tool?

This tool help you gather data for chess players in a single place.
This help you prepare for tournaments, researching about your potential opponents. 

Some use cases 
1. You play in your local club, city often and you want to research and track your frequently met opponents
2. You want to prepare for your next tournament. Who are you potential opponents? What are their most played openings?

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
