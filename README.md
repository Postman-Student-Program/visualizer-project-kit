# Postman Visualizer Project Kit

Data is as powerful as it is understandable. This kit will help you build a hosted project that makes sense of data from APIs. Postman’s [visualizer](https://learning.postman.com/docs/sending-requests/visualizer/) feature can help you prototype your visualization if you plan to use JavaScript in your project.

Create a free Postman account [here](https://www.postman.com/) and [sign up as a Postman Student Expert]() if you haven't already!

## 1. Decide what you want to show
What story are you trying to tell, o
r what tool are you trying to build?

Once you can answer that, there are several ways to find APIs that give you relevant data.

## 2. Find data via an API

You'll need data! There are any ways to discover APIs that give you the data you need. Here are a few:

### Postman API Network
This is a great place to start since APIs on Postman's API Network have collections ready for you to fork and immediately play with!

Search for APIs directly in Postman using the Search bar at the top, or by clicking the "Explore" tab and searching APIs by category.

<img width="700" alt="image" src="https://user-images.githubusercontent.com/9841162/227543200-11921d15-bb92-44c5-9d4d-b8be3fad5da4.png">

Note that anyone can publish APIs and collections to Postman's network, so check the author and lean on entities that match the source organization. If you don't see a workspace by the source organization itself, authors such as "Postman" and "Postman DevRel" tend to publish quality content. 

### Look for government APIs
World governments often make their datasets available via APIs. Try searching for something like "US population data APIs", "India historical climate data APIs" and see what you find. 

For example, the US government has a selection of [Census related APIs](https://www.census.gov/data/developers/data-sets.html), and New York City has the [NYC Open Data](https://opendata.cityofnewyork.us/) resource which houses many interesting APIs related to city data.  

### Search online

Use a search engine or AI search to find APIs for other data/services you are interested in. For example, searching "Spotify API" will take you to their API docs that tell you how to get started. 

### Ask ChatGPT 

Ask ChatGPT to list APIs relevant to the data you are trying to find.

ex: "List 10 weather data APIs, with links to their documentation"

### Host your own data!

Have data you want to share with the world? You've got options!

- Use [Postman mock servers](https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/) to "fake" an API to publicly serve your data over the web. Good for limited usage. This [quick video](https://www.youtube.com/watch?v=n_7UUghLpco) will help you set it up!
- Host a JSON file for free on websites like [GitHub](https://github.com/) and access it via a `GET` request to the hosted raw file URL. Check out these [public JSON datasets](https://github.com/jdorfman/awesome-json-datasets) for inspiration!
- Build and host your own custom API (more advanced)

## 3. Visualize your data with code

Fork a starter template of your choice and follow the instructions in the comments and README.md to display a production version of your visualization

- [Vanilla HTML/JS/CSS starter template](https://replit.com/@postman/NYC-Subway-Ridership-API-data-visualization-example)
- [React starter template](https://replit.com/@postman/NYC-Subway-Ridership-React-API-data-visualization-ex)
- [Python starter template (Google Colab*)](https://colab.research.google.com/drive/1cdJUlFub--p_1RQ4913RxJDtR957EXdo?usp=sharing)

*requires a Google account

### Useful visualization libraries

JavaScript (vanilla)
- [ChartJS](https://www.chartjs.org/docs/latest/)
- [d3.js](https://observablehq.com/@d3/gallery)
- [Highcharts](https://www.highcharts.com/)

React 
- [Recharts](http://recharts.org/en-US/)
- [Victory](https://formidable.com/open-source/victory/)
- [d3.js](https://observablehq.com/@d3/gallery) with React wrapper libraries like [d3-react-component](https://www.npmjs.com/package/d3-react-component)

Python
- [Matplotlib](https://matplotlib.org/api/index.html)
- [Plotly](https://plot.ly/python/)
- [Seaborn](https://seaborn.pydata.org/)

### [Optional] Prototype your visualization in Postman!
If you plan to use JavaScript to visualize your data, you can protoype your visualization right in Postman using the [visualizer](https://learning.postman.com/docs/sending-requests/visualizer/) feature! 

Check out [this Postman workspace](https://www.postman.com/postman/workspace/more-visualizer-examples) for a bunch of Postman visualization examples, including charts, maps and more!
