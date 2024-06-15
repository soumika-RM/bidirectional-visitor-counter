# Bidirectional Visitor Counter

This Arduino project implements a bidirectional visitor counter using sensors and an LCD display.

## Components Used

- Arduino Uno
- LCD Display (with I2C interface)
- IR Sensors
- Relay Module

## Installation

1. **Clone the Repository**: git clone https://github.com/soumika-RM/bidirectional-visitor-counter
2. **Upload Code to Arduino**:
- Open `bidirectional_visitor_counter.ino` in Arduino IDE.
- Connect your Arduino board via USB.
- Select the correct board and port in Arduino IDE.
- Upload the code to your Arduino.

## Usage

- Adjust sensor pins (`sensorPin1` and `sensorPin2`) in the code based on your actual setup.
- The counter increases with one sensor activation and decreases with the other.
- LCD displays current visitor count and status.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


