# plotly-window-plotter
A website that is intended to display a plotly plot in it's own window using query strings as the data


## Description
Plotly plots generally take two parameters,  data and layout.  This application searches the querystring for 'data' and 'layout' parameters and if it finds them will attempt to generate the plotly plot.  The Query parameters should be base64 encoded JSON.

