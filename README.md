# Blazor Web App with jQuery Autocomplete

This is a Blazor web application built using .NET that demonstrates the use of jQuery Autocomplete feature to fetch and display data dynamically from an external API. The application allows users to input information about countries, harbors, and goods, and calculates tariff rates based on the provided data.

## Features

- Autocomplete for country and harbor inputs, fetching data from an external REST API ([mock-harbor-api](https://github.com/irfans18/mock-harbor-api))
- Autofetching goods information based on user input
- Calculation of tariff rates based on provided price and population data

## Technologies Used

- **Blazor**: A web framework for building interactive web UIs with .NET
- **jQuery**: A fast, small, and feature-rich JavaScript library for DOM manipulation
- **REST API**: Used to fetch country information from [mock-harbor-api](https://github.com/irfans18/mock-harbor-api)

## Setup

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/irfans18/dotnet-form-autocomplete.git
   ```

2. Open the solution in Visual Studio or your preferred IDE.

3. Run the application using IIS Express or your preferred development server.

4. Navigate to the specified URL in your web browser to access the application.

## Usage

1. Enter the name of a country in the "Negara" input field. Autocomplete suggestions will be displayed based on the input.
2. Enter the name of a harbor in the "Pelabuhan" input field. Autocomplete suggestions will be displayed based on the input.
3. Enter the ID of a good in the "Barang" input field. Autocomplete suggestions will be displayed based on the input.
4. Enter the price of the good in the "Harga" input field. The tariff rate will be calculated automatically based on the price and population data fetched from the API.

## Dependencies

- [jQuery](https://jquery.com/)
- [jQuery UI](https://jqueryui.com/)

## Credits

- The autocomplete feature is powered by the [jQuery UI Autocomplete](https://jqueryui.com/autocomplete/) widget.
- Country information is fetched from the [restcountries.com](https://restcountries.com) API.
