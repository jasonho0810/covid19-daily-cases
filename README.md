# COVID-19 Daily Confirmed Cases In Ontario and Hong Kong
Medium blog post 1: https://medium.com/@jasonho_83059/covid-19-a-contrast-between-hong-kong-and-ontario-canada-e133bb95c9e2

Medium blog post 2: https://medium.com/@jasonho_83059/response-to-covid-19-in-ontario-fc8e3557e52d

I am interested in Ontario and Hong Kong because I live in Toronto Ontario and much of my familiy lives in Hong Kong. 
However, that does not take away from the commonalities they share in this pandemic. 
More information is in the blog posts on Medium linked above. 
The first blog post fits a Generalized Additive Model to daily confirmed cases in Ontario and Hong Kong for a smooth time trend. 
The second blog post fits an additive Time Series model to daily confirmed cases in Ontario for forecasting.
An upcoming third blog post will fit a Generalized Additive Mixed Model to daily confirmed cases in Ontario to extrapolate to uninfected countries.

All statistical analysis can be performed by running the respective Jupyter notebook scripts.

## Installations
```python3
pip3 install -r requirements.txt
```
* NumPy, pandas
* GLMGam, BSplines
* pycountry
* Prohpet
* Plotly

## Datasets
* Confirmed cases and deaths by province and country: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series
* Confirmed cases, deaths, recovered cases, and active cases by province and country: https://api.covid19api.com
* Government response tracker 'Stringency' index by country: https://covidtrackerapi.bsg.ox.ac.uk/api/stringency

## File Descriptions
* `covid19-daily-confirmed-cases.ipynb` - script to extract dataset, clean the data, fit a Generalized Additive Model, and generate all descriptive and inferential statistics in the first blog post.
* `covid19-cases-forecast.ipynb` - script to extract dataset, clean the data, fit an additive Time Series Model, and generate all descriptive and inferential statistics in the second blog post.

## Licensing, Authors, and Acknowledgements
[MIT License](https://github.com/jasonho0810/covid19-daily-confirmed-cases/blob/master/LICENSE)
