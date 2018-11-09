# biodiversity-plotly.js

In this assignment, I created a dashboard to show various aspects of belly button biodiversity data. First, the user selects a bacteria sample, the data of which is then fetched using `flask-sqlalchemy`. After the sample data is collected, it is passed to the pie chart, the bubble chart, and the gauge chart, all of which were created using Plotly.js. When the user selects a new sample, each chart is overwritten.

## Prerequisites

The CDNs for D3, Plotly.js, and Bootstrap are linked in `index.html`. Source data can be found in `db/bellybutton.sqlite` and was obtained from somewhere reputable, presumably.

## Built With

* Javascript (D3)
* HTML 5.0
* [Bootstrap](https://getbootstrap.com/)
* [Plotly.js](https://plot.ly/javascript/)
* Flask-sqlalchemy
* Pandas

## Authors

* Arley Schenker