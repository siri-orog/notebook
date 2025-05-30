import pandas
!wget https://raw.githubusercontent.com/MicrosoftDocs/mslearn-introduction-to-machine-learning/main/m0b_optimizer.py
!wget https://raw.githubusercontent.com/MicrosoftDocs/mslearn-introduction-to-machine-learning/main/Data/seattleWeather_1948-2017.csv
# Load a file that contains weather data for Seattle
data = pandas.read_csv('seattleWeather_1948-2017.csv', parse_dates=['date'])
# Keep only January temperatures
data = data[[d.month == 1 for d in data.date]].copy()
# Print 
import pandas
!wget https://raw.githubusercontent.com/MicrosoftDocs/mslearn-introduction-to-machine-learning/main/m0b_optimizer.py
!wget https://raw.githubusercontent.com/MicrosoftDocs/mslearn-introduction-to-machine-learning/main/Data/seattleWeather_1948-2017.csv
# Load a file that contains weather data for Seattle
data = pandas.read_csv('seattleWeather_1948-2017.csv', parse_dates=['date'])
# Keep only January temperatures
data = data[[d.month == 1 for d in data.date]].copy()
# Print the first and last few rows
# Remember that with Jupyter notebooks, the last line of 
# code is automatically printed
data
Connecting failed. Please reload and try again.the first and last few rows
# Remember that with Jupyter notebooks, the last line of 
# code is automatically printed
data
