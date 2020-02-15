# Pubmed Citation Generator [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)


Writing citations for research papers is time-consuming!

Great news, NCBI’s databases (web API) are accessible using Python. Thus, this program can create MLA citations for the first *five* articles found.

## Demo 

<img src="https://github.com/ying-li-python/citation-generator/blob/master/Images/citation-demo.gif?raw=true" height="60%">

## Featured 
Here's a [step-by-step tutorial](https://yingli.dev/blog/posts/2020-01-30-generate-citations-with-python.html) on how I wrote the program.

## How it works 
When running the script in terminal, you will be asked to enter search terms to find your articles. Results will display the PubMed ID and citation for each of the five articles. 

For example, the search terms "big data ETL" results in (only 1 out of 5 shown): 
```
python3 main.py 
Please enter a search for PubMed articles: big data ETL
------------------------
Beginning article search
------------------------
Retrieving articles 1 of 5
PubMed ID: 31201587
Godinho TM, Lebre R, Almeida JR, Costa C. ETL Framework for Real-Time Business Intelligence over Medical Imaging Repositories. J Digit Imaging 2019;32(5):870-879. doi: 10.1007/s10278-019-00184-5
------------------------
```


## Prerequisites
- Python3
- Basic knowledge of data parsing and web API 

## Requirements
- Install [requests](https://www.pythonforbeginners.com/requests/using-requests-in-python) (Python module)

## Resources 
- [NCBI's Entrez (API)](https://www.ncbi.nlm.nih.gov/books/NBK25500/) 

## Getting started 
Clone the repository from github and go into the peptide-search folder in terminal.
```
git clone https://github.com/ying-li-python/citation-generator.git
cd citation-generator
```

## Running the script 

Run the script in terminal and enter search terms to find your article.
```
python3 main.py
```

## Results 
You should see the first five articles showing its unique PubMed ID and citation written in MLA format. 

Good luck! 

## Author
Ying Li 
