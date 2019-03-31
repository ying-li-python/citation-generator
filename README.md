# pubmed-search-api

Writing citations for research papers is time-consuming! Instead, let's use Python to access NCBI's PubMed database when we want to retrieve article information and help create a citation in MLA format for the first *five* articles found. 

## Prerequisites
- Python3
- Basic knowledge of data parsing and web API 

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
