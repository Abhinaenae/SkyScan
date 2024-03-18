# Skyscan

Skyscan is a command-line tool written in Go that fetches and displays weather information for a specified city.

## Usage

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Abhinaenae/SkyScan
   ```

2. **Build the Executable**

   Navigate to the directory containing the source code and build the executable using the following command:

   ```bash
   go build -o skyscan
   ```

3. **Run the Tool**

   Once the executable is built, you can run the tool by executing the following command:

   ```bash
   ./skyscan <city-name>
   ```

   Replace `<city-name>` with the name of the city for which you want to retrieve weather information. If no city name is provided, it defaults to "Dallas". The default can changed by editing `q` on line 40 to be any city.

## Example

![londonexample](https://github.com/Abhinaenae/SkyScan/assets/92381984/2be56a62-a70e-4512-be48-08f9c1a970d2)

## Dependencies

This tool depends on the following external packages:

- [github.com/fatih/color](https://github.com/fatih/color) - For terminal color output.
- [Go](https://go.dev/dl/)

## API Used

This tool utilizes the [WeatherAPI](https://www.weatherapi.com/) to fetch weather data. You will need to make your own API key.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
