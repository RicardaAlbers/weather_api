# About this notebeeok
 
In this notebook, I use the OpenWeatherMap geocoding API to retrieve the geographic coordinates of 4 German cities (Hamburg, Düsseldorf, Berlin and Munic). My goal is to then retrieve the current weather in these cities from OpenWeatherMap and perform further analysis. I will use Python, the Pandas library and Requests to collect and analyze the data.

[www.openweathermap.org]('https://openweathermap.org/')

The primary goal of this notebook is to demonstrate the process of working with APIs to collect and analyze weather data, as well as to visualize the findings. 


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