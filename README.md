# About this notebeeok

In this notebook, I will examine the change in weather over the last 40 years in the Ruhr region. <br>
I work with data that I query via [www.openweather.org]('https://openweathermap.org/'). Since I am not a weather expert, but this notebook is mainly for training purposes (on the one hand the query of APIs on the other hand the visualization of data), I limit myself to the observation of temperature and precipitation at four locations in the Ruhr area. These locations are: Duisburg, Essen, Bochum and Dortmund. A map of the Ruhr area can be found [here]('https://de.wikipedia.org/wiki/Ruhrgebiet#/media/Datei:Ruhr_area-administration.png').


## Requirements and Environment

Requirements:
- pyenv with Python: 3.11.3

Environment: 

For installing the virtual environment you can either use the Makefile and run `make setup` or install it manually with the following commands: 

```Bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt