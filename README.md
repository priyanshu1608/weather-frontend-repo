# Weather App

## Select Country

- Select country from the dropdown.
- Can type country name and it will filter down the options for you.

## Select City

- Once Country is selected, Dropdown for select city will be visible.
- Select City from the dropdown.
- Can type city name to filter down the options.
- Once city is selected, submit button will be enabled to get weather data.
- Note: If Country is changed, city selected earlier will be removed and need to select city again.

## Weather Data

- Once the weather data will be fetched from backend it will be shown in a card with city name and current temperature and humidity.

## How to run application

- Install npm with version 6.14.18 and node version 14.21.3
- `npm install` -> run to download all dependencies
- create a .env in root directory(weather-frontend-repo) with variable `REACT_APP_API_URL='http://localhost'` and `REACT_APP_PORT='3001'
` as backend is running on port 3001
- `npm start` -> to run application
- application will start at port 3000