# thesis-dataset
Dataset Collection for [Thesis](https://github.com/putuwaw/thesis).

## Features
- Raw dataset (captions & comments) for Balinese text classification: [instagram.json](instagram.json)
- Some of the Instagram account source:
  - [@lanmalajah.id](https://www.instagram.com/lanmalajah.id/)
  - [@basabali.id](https://www.instagram.com/basabali.id/)
  - [@basabaline](https://www.instagram.com/basabaline/)
  - [@melajahbahasabali](https://www.instagram.com/melajahbahasabali/)
- Example scraping data (captions & comments) from various social media: [dataset.json](dataset.json)
- Notebook for scraping data: [notebook.ipynb](notebook.ipynb)
- Notebook for pre-processing dataset: [preprocessing.ipynb](preprocessing.ipynb)
  - Dataset will be anotated by Penyuluh Bahasa Bali: [dataset.xlsx](dataset.xlsx)
  - Dataset annotation result: [thesis-ml/dataset](https://github.com/putuwaw/thesis-ml/tree/main/dataset) 

## Prerequisites
This project mainly using Selenium and BeautifulSoup4 for scraping data from various social media.
So, you basically need:
- Webdriver for Selenium (Chrome in this project)

## Installation
- Clone the repository:
```
git clone https://github.com/putuwaw/thesis-dataset.git
```
- Install dependencies:
```
pip install -r requirements.txt
```
- If dependencies failed, you can try to install:
```
pip install ipykernel selenium beautifulsoup4 pydantic pandas linggapy openpyxl requests
```
- You are ready for scraping and collecting data.
