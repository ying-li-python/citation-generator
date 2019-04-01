# pubmed-search-api

Writing citations for research papers is time-consuming!

Great news, I have created a Python program that accesses NCBI’s PubMed database (web API) and after retrieving article information, MLA citations are made for the first *five* articles found.

## Featured 
A step-by-step tutorial on how I wrote the program can be found [here](https://creativepython.wordpress.com/2019/04/01/biologypython-retrieve-ncbis-pubmed-articles-and-create-citations-with-python-tutorial/).

## Prerequisites
- Python3
- Basic knowledge of data parsing and web API 

## Requirements
- Install [Requests](https://www.pythonforbeginners.com/requests/using-requests-in-python) (Python module)

## Resources 
- [NCBI's Entrez (API)](https://www.ncbi.nlm.nih.gov/books/NBK25500/) 

## Getting started 
Clone the repository from github and go into the peptide-search folder in terminal.
```
git clone https://github.com/ying-li-python/pubmed-search-api.git
cd pubmed-search-api
```

## Running the script 

Run the script in terminal
```
python main.py
```

You will be asked to enter search terms used to search articles. 

## Results 
You should see the first five articles showing its unique PubMed ID and citation written in MLA format. 

Results for "drosophila circadian clock" (my research focus) as an example:

<img src="https://raw.githubusercontent.com/ying-li-python/pubmed-search-api/master/Images/results.png"> 

Good luck! 

## Author
Ying Li 
