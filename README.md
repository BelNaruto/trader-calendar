# Trader Calendar API

The **Trader Calendar API** provides essential information for traders and financial analysts by offering access to a comprehensive calendar of financial events, earnings reports, economic indicators, and more. This API is designed to help users stay informed about key market-moving events and integrate this data seamlessly into their applications and analysis tools. This API can be founf [here](https://rapidapi.com/belchiorarkad-FqvHs2EDOtP/api/trader-calendar-api)

## Key Features

- **Financial Events Calendar**: Access a detailed calendar of upcoming financial events, including earnings reports, economic indicators, and market holidays.
- **Real-Time Updates**: Stay up-to-date with real-time updates on events that can impact financial markets.
- **Event Details**: Retrieve detailed information about each event, including dates, times, and descriptions.
- **Customizable Alerts**: Set up alerts for specific events to ensure you never miss important updates.

## Getting Started

1. **Sign Up**: Create an account on RapidAPI.
2. **Subscribe**: Select a subscription plan that fits your needs.
3. **API Key**: Obtain your unique API key to start making requests.
4. **Documentation**: For detailed usage instructions, visit the [Trader Calendar API Documentation](https://rapidapi.com/belchiorarkad-FqvHs2EDOtP/api/trader-calendar-api).


## Endpoint: /calendar

### Description:
This endpoint retrieves economic events data based on the specified query parameters.

### Method:
GET

### Parameters:
- **from_date** (optional): The start date to retrieve economic events from. Format: 'dd/mm/yyyy'.
- **to_date** (optional): The end date to retrieve economic events up to. Format: 'dd/mm/yyyy'.
- **countries** (optional): A comma-separated list of country codes to filter economic events by.

### Response:
- **200 OK**: Returns JSON data containing economic events.
- **400 Bad Request**: If an error occurs during processing, returns JSON data with an error message.

### Example Request:
```http
GET /calendar?from_date=2024-04-01&to_date=2024-04-30&countries=US,UK HTTP/1.1
Host: example.com
```

## Commonly Asked Questions

### 1. What kind of data can I access through the Trader Calendar API?
You can access a comprehensive calendar of financial events, including earnings reports, economic indicators, and market holidays.

### 2. How do I authenticate my API requests?
You need to include your API key in the headers of your requests as specified in the API documentation.

### 3. Are there usage limits for the API?
Yes, usage limits depend on the subscription plan you choose. Check the RapidAPI dashboard for specifics.

### 4. Can I set up alerts for specific events?
Yes, the API allows you to set up customizable alerts for specific events to ensure you receive timely updates.

### 5. Is historical data available for past events?
Currently, the Trader Calendar API focuses on upcoming and real-time events. For historical data availability, please refer to the API documentation.

For more information and to start using the Trader Calendar API, visit [Trader Calendar API on RapidAPI](https://rapidapi.com/belchiorarkad-FqvHs2EDOtP/api/trader-calendar-api).
