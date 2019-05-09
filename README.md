# Pubmed Citation Generator

Writing citations for research papers is time-consuming!

Great news, NCBI’s databases (web API) are accessible using Python. Thus, this program can create MLA citations for the first *five* articles found.

## Featured 
A step-by-step tutorial on how I wrote the program can be found [here](https://creativepython.wordpress.com/2019/04/01/biologypython-retrieve-ncbis-pubmed-articles-and-create-citations-with-python-tutorial/).

## How it works 
When running the script in terminal, you will be asked to enter search terms to find your articles. Results will display the PubMed ID and citation for each of the five articles. 

For example, the search terms "drosophila circadian clock" (my research focus) results in (only 1 out of 5 shown): 
```
python main.py 
Please enter a search for PubMed articles: drosophila circadian clock 
------------------------
Beginning article search
------------------------
Retrieving articles 1 of 5
PubMed ID: 30881291
Chen W, Xue Y, Scarfe L, Wang D, Zhang Y. Loss of <i>Prune</i> in Circadian Cells Decreases the Amplitude of the Circadian Locomotor Rhythm in <i>Drosophila</i>. Front Cell Neurosci 2019;13():76. doi: 10.3389/fncel.2019.00076
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
git clone https://github.com/ying-li-python/pubmed-search-api.git
cd pubmed-search-api
```

## Running the script 

Run the script in terminal and enter search terms to find your article.
```
python main.py
```

## Results 
You should see the first five articles showing its unique PubMed ID and citation written in MLA format. 

Results for "drosophila circadian clock" as an example:

<img src="https://raw.githubusercontent.com/ying-li-python/pubmed-search-api/master/Images/results.png"> 

Good luck! 

## Author
Ying Li 
