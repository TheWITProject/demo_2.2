## Summary
You will be demoing using Postman to write a `GET` request to a public API. You will also be demoing how to configure a `POST` request (but not actually sending it since this public API does not accept `POST` requests.

## Instructions
[Rates API](https://ratesapi.io/) is an API for current and historical foreign exchange rates.

You can use `https://api.ratesapi.io/api/latest` to `GET` all of the most recent exchange rates.

You can also use `https://api.ratesapi.io/api/2010-01-12` to `GET` all of the the exchange rates on some day. The date here might be expressed as a variable route in Flask.

You can use `ttps://api.ratesapi.io/api/2010-01-12?base=GBP` to `GET` all of the exchange rates on some day with a specified base currency. The currency here might be expressed as a query parameter in Flask.

Rates API does not have any `POST` routes. This one will be mocked, but be sure to demonstrate how to change the verb and append data to the request body. Use the JSON format.

If you have time, exercise_2.2 will require students sign up for the [Google Cloud Console](https://cloud.google.com/). Please demo how to register and get an API key. Instructions found [here](https://developers.google.com/maps/gmp-get-started).
