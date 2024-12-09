# tech-ex-pana
Technical Exercise
1. I have used Python 3.11.3
2. Code is in Jupyter Notebook
3. Libraries used : 
	-requests
	-pandas
	-from dotenv import dotenv_values
	-json
	-os
	-time
	-re
4. ".env" created which stores API_KEY. This fill will be added to ".gitignore"
5. cocktail_raw.ipynb will run prior to cocktail_etl.ipynb:
	1. raw pipeline extracts raw json files
	2. etl pipeline picks raw files and does transformation and loads to cocktail.csv
6. This is covered in Choice.docx file.
