# Weather App Built using Go

## Steps to run

- Make an account on https://api.weatherapi.com/ and get your API key.
- Copy the .env.test file to a .env file and replace API_KEY variable with your own API key.
- Run the following command to install the required packages

```
$ go mod tidy
```

- Run the following command and replace the city name with the city you want to get the weather details.

```
$ go run main.go CITY_NAME
```