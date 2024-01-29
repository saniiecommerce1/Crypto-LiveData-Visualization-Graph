# Crypto-LiveData-Visualization-Graph
Project Introduction:
APIs:
Basically in this project third party APIs of coingecko.com is used for retreiving the data of digital coin.
https://www.coingecko.com/api/documentation
1. For Top Trending: "https://api.coingecko.com/api/v3/search/trending"
2. For Searching:  'https://api.coingecko.com/api/v3/search?query=${search}'
3. For Graphs: 'https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc&per_page=7&page=1&sparkline=false&price_change_percentage=24h&locale=en'
4. For Charts as per the specified data : 'https://api.coingecko.com/api/v3/coins/${id}/market_chart?vs_currency=${currency}&days=${days}&precision=${precision}'
Used redux thunk for storing the fetched and manipulated data.
Pages:
Created different pages like Home page, Search page , Trending, TrendingOne(details of one trending coin), SearchOne(details of one search coin)
Components:
Different components like PieChart (visualized the data in te form of pie chart), TopBox(show the top trending data), BarChart(data represent in the form of bars) , as per the data that is fetched from API. Navbar, Footer, MenuBar these are also another components.
TypeScript:
In the dataInterface.ts file all the types of variable is declared,defined and export. 
NPM packages: 
1. Redux tool kit for state managing
2. Recharts as UI for data graph and chart visualization
3.   Axios for fetching data
4. Sass and material UI for styling
5. React circular progress bar for loading
6. 
7. Deploy on Netflix:
https://65b748394d919af58bbf54a1--elaborate-sprite-b1a56e.netlify.app/

