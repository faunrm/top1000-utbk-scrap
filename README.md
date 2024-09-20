# UTBK Top 1000 Schools Scraper

This repository contains a Python Jupyter Notebook that scrapes data of the top 1000 schools based on UTBK scores. The notebook extracts, processes, and saves the data for further analysis.

Table of Contents : 
* Description
* Requirements
* How to Use
* Output
* Contributing
* License

## Description

The UTBK Top 1000 Schools Scraper is designed to scrape publicly available data from a website or platform that lists the top 1000 schools based on UTBK scores. The main purpose of this notebook is to gather and store the information in a structured format, making it easier to analyze or visualize.

## Requirements
To run this notebook, you will need:

* Python 3.x
* Jupyter Notebook or JupyterLab
* The following Python libraries:
	* `requests`
	* `BeautifulSoup`
  * `pandas`

You can install the required libraries using:

```
pip install -r requirements.txt
```

## How to Use
1. Clone this repository:

	```
	git clone https://github.com/yourusername/utbk-top-1000-schools-scraper.git
	```

2. Navigate to the directory and launch the Jupyter Notebook:

	```
	cd utbk-top-1000-schools-scraper
	jupyter notebook SCRAP_TOP_1000_UTBK.ipynb
	```
3. Execute the cells in the notebook sequentially to scrape the data.

4. After running the notebook, you will get the scraped data in a structured format, typically saved as a CSV file.

## Output
The notebook will output a CSV file containing the following columns:

* Peringkat : The rank of the school based on UTBK scores.
* NPSN : National School Identification Number
* Provinsi : The province where the school is located.
* Kota/Kabupaten : The city where the school is located.
* Jenis : The type of the school (SMA, MA, SMK, Paket C).
* Nilai Total : The average of all score from every subtest.
* PK : The average score of Pengetahuan Kuantitatif (quantitative knowledge) subtest
* PBM : The average score of Pemahaman Bacaan dan Menulis (reading comprehension and writing) subtest
* PU : The average score of Penalaran Umum (general reasoning) subtest
* PPU : The average score of Pengetahuan dan Pemahaman Umum (general knowledge and understanding) subtest


## Contributing
Feel free to fork the repository, make improvements, and submit a pull request. Contributions to enhance the scraper or add more features are welcome.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
