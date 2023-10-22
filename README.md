# Airbnb Data Visualization Dashboard

This is a dashboard app to visualize and analyze Airbnb listing data. 

## Overview

- The data is stored in a MongoDB database hosted on MongoDB Atlas. 
- The raw data is cleaned and preprocessed into a Pandas DataFrame.
- The app is built using Python, Pandas, Streamlit for the front-end, and Plotly for the visualizations.

## Features

The dashboard provides:

- An overview tab with summaries and insights into the data
- Interactive filters to slice and dice the data
- Visualizations including bar charts, pie charts, box plots, geographic charts
- Analysis of price, property types, availability across locations

## Usage

To run the app:

- Install the required libraries (`pandas`, `streamlit`, `plotly` etc) 
- Configure the MongoDB database connection
- Run `streamlit run app.py` to start the app
- Use the sidebar filters to analyze different cuts of the data
- Navigate between overview and explore pages for more insights

## Data

The data is sourced from Airbnb listings and stored in the `listingsAndReviews` collection in MongoDB Atlas. 
The raw data is preprocessed into a cleaned Pandas DataFrame for easier analysis.

## Customization

The app can be extended by:

- Adding more interactive filters and slicers
- Including new metrics and visualizations
- Connecting to live data sources instead of static dataset
- Deploying to a server for public access

## License

MIT

This provides an overview of the project with information on the technologies used, key features, usage instructions, data source and customization options. Let me know if you would like me to modify or expand the README file further.
