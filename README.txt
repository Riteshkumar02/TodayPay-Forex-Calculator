1.First Clone the project or download zip folder
git clone https://github.com/YOUR_USERNAME/currency-converter.git

2.install the dependencies:
cd currency-converter
npm install


3. To start the development server
npm start
Open a web browser and go to http://localhost:3000


API

4.The currency converter application uses the ExchangeRate API to get exchange rates. You can interact with the API directly by making HTTP requests to the following endpoints:

GET https://api.exchangerate-api.com/v4/latest/:base
This endpoint returns the latest exchange rates for the specified base currency. For example, to get the latest exchange rates for USD, you would make a GET request to https://api.exchangerate-api.com/v4/latest/USD.
GET https://api.exchangerate-api.com/v4/fluctuations/:base/:target

This endpoint returns the historical exchange rates for the specified base and target currencies. For example, to get the historical exchange rates for USD and EUR, you would make a GET request to https://api.exchangerate-api.com/v4/fluctuations/USD/EUR.
Both of these endpoints return JSON objects
