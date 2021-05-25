# fpl-ml-bar-chart-race

This repository contains the Jupyter notebook for creating a bar chart race for a FPL classic mini league. The code pulls manager performace data from the FPL API, transforms it and creates a bar chart race. User needs to input the classic league id and the number of managers for which the chart has to be created.

**Prerequisites:**
  1. The code uses f-strings, so Python 3+ is needed
  2. User needs to install [bar-chart-race](https://pypi.org/project/bar-chart-race/) package to create the chart
  3. bar-chart-race package requires FFmpeg in order to function. Detailed guide to download and install FFmpeg can be found [here](https://www.wikihow.com/Install-FFmpeg-on-Windows) 

**Points to Note:**
  1. Classic league id can be obtained from the URL of the league. For example, in the URL https://fantasy.premierleague.com/leagues/123456789/standings/c, the league id would be 123456789
  2. In case the mini league has >50 managers, the FPL API returns data only for top 50 managers by rank
