# Home Weather Station

This Arduino sketch enables you to create a Home Weather Station using Arduino IoT Cloud with BMP280 and DHT11 sensors.

## Features

- Reads temperature, pressure, and altitude from BMP280 sensor
- Reads humidity from DHT11 sensor
- Updates data to Arduino IoT Cloud dashboard
- Displays data on the Serial Monitor

## Hardware Requirements

- Arduino board (e.g., Arduino Uno, ESP32)
- BMP280 sensor
- DHT11 sensor
- Wires for connections

## Installation

1. Install the required libraries:
   - Adafruit BMP280 library
   - DHT library

2. Set up your Arduino IoT Cloud Thing and obtain the necessary credentials.

3. Update `thingProperties.h` with your IoT Cloud credentials.

4. Connect BMP280 and DHT11 sensors to your Arduino board.

5. Upload the sketch to your Arduino board.

6. Monitor the data on both the Serial Monitor and Arduino IoT Cloud dashboard.

## Usage

1. Open the Arduino IDE and upload the sketch to your Arduino board.

2. Open the Serial Monitor to view the sensor readings.

3. Check the Arduino IoT Cloud dashboard for real-time data.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

