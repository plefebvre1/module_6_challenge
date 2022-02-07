# Module 6 Challenge

This Jupyter notebook contains an analysis of the San Fransisco real estate enviroment that compares rental income and sales prices over time and by neighborhood. Initally, we confirmed that the number of housing units consistently grew over time in SF:
![SFHousingUnits](/Images/zoomed-housing-units-by-year.png)

Over all neighborhoods, rental income and sales prices increase at the same time:
![AllSFPlot](/Images/avg-sale-px-sq-foot-gross-rent.png)

However, certain neighborhoods do not follow this trend and an interactive chart was built to be able to see which neighborhoods do not follow this trend. Alamo Square is an example of a neighborhood that does not follow the overall trend:
![AlamoSqPlot](/Images/pricing-info-by-neighborhood.png)

In addition to the above charts, an interactive geospatial chart of average rental income and sales prices by neighborhood is included at the bottom of the notebook with our final results:
![GeoPlot](/Images/6-4-geoviews-plot.png)

## Technologies

This project leverages Python 3.7 in Jupyter Lab with the following packages:

* [pandas](https://pandas.pydata.org/) - For financial data analysis tools
* [hvplot](https://hvplot.holoviz.org/) - For interactive data visualizations

## Contributors

Starter code for this app was provided by the GWU Fintech Bootcamp program. Updates to that code to fulfill the analysis were done by Peter Lefebvre (peter.c.lefebvre@gmail.com)

## License

MIT License
