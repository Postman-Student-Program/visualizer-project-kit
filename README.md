# Postman Visualizer Project Kit

Data is as powerful as it is understandable. This kit will help you build a hosted project that makes sense of data from APIs with the help of Postman’s [visualizer](https://learning.postman.com/docs/sending-requests/visualizer/) feature

Create a free Postman account [here](https://www.postman.com/) and [sign up as a Postman Student Expert]() if you haven't already!

## 1. Find data via an API

First you'll need data to visualize! What story are you trying to tell? Once you can answer that, there are several ways to find APIs that give you related data.

### Postman API Network
Search for APIs directly in Postman using the Search bar at the top, or by clicking the "Explore" tab and searching APIs by category.

<img width="700" alt="image" src="https://user-images.githubusercontent.com/9841162/227543200-11921d15-bb92-44c5-9d4d-b8be3fad5da4.png">

Note that anyone can publish APIs and collections to Postman's network, so check the author and lean on entities that match the source organization. Authors such as "Postman" and "Postman DevRel" tend to publish quality content, too. 

### Look for government APIs
World governments often make their datasets available via APIs. Try searching for something like "US population data APIs", "historical climate data APIs" and see what you find. 

For example, the US government has a selection of [Census related APIs](https://www.census.gov/data/developers/data-sets.html).  
### Search online

Use a search engine or AI search to find APIs for other data/services you are interested. For example, searching "Spotify API" will take you to their API docs that tell you how to get started. 
### Host your own data!

Have data you want to share with the world? You've got options!

- Build and host your own custom API
- Use [Postman mock servers](https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/) to "fake" an API to publicly serve your data over the web
- Host a JSON file for free on websites like [GitHub](https://github.com/) and access it via a `GET` request to the hosted file URL. Check out these [public JSON datasets](https://github.com/jdorfman/awesome-json-datasets) for inspiration!

## 2. Decide how you want to visualize the data

**TODO: Link to example visualizations and viz libraries (d3js, chartjs, etc)**
JavaScript
- [ChartJS](https://www.chartjs.org/docs/latest/)
- [d3.js](https://observablehq.com/@d3/gallery)
- [Highcharts](https://www.highcharts.com/)

Python
- [Matplotlib](https://matplotlib.org/api/index.html)
- [Plotly](https://plot.ly/python/)
- [Seaborn](https://seaborn.pydata.org/)

## 3. Prototype your visualization in Postman!

**TODO: Add visualizer resources + video**

## 3. Add your visualization to your project

Fork a starter template of your choice and follow the instructions in the comments and README.md to display a production version of your visualization

- [Vanilla HTML/JS/CSS starter template](https://replit.com/@postman/NYC-Subway-Ridership-API-data-visualization-example)
- React starter template
- [Python starter template (Google Colab*)](https://colab.research.google.com/drive/1cdJUlFub--p_1RQ4913RxJDtR957EXdo?usp=sharing)

*requires a Google account


