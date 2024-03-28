# FuelFinder360

## Introduction
FuelFinder360 is a comprehensive tool designed to ease the search for the most economical fueling options. By combining a Swift-developed iOS application with Python scripts for processing real-time data from CSV files, FuelFinder360 offers an unparalleled resource for drivers. Users can explore fuel prices, discover the cheapest or nearest gas stations, and contribute by updating prices, all within a seamless mobile experience. The backend Python scripts ensure the app's fuel price data remains current by parsing daily updated CSV files from authoritative sources, making FuelFinder360 a reliable companion for any driver looking to save on fuel.

## Features
- **Up-to-Date Fuel Prices**: Access current fuel prices for various types at nearby stations.
- **Station Locator**: Find gas stations based on price or proximity with comprehensive details.
- **Community Updates**: Users can contribute by reporting the latest fuel prices.
- **Data-Driven**: Utilizes Python scripts to parse and update fuel price data from CSV files.

## Technology Stack
- **iOS Application**: Developed in Swift, utilizing UIKit and CoreLocation.
- **Data Processing**: Python scripts for parsing CSV files and updating the app's database.

## Getting Started

### Prerequisites
- Xcode 12 or later for iOS app development
- Python 3.x for running data processing scripts

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/cgio2003/FuelFinder360.git
   ```
2. Navigate to the iOS project directory and open FuelFinder360.xcodeproj in Xcode.
Install necessary Swift package dependencies as prompted by Xcode.
Python Scripts
3. Ensure Python 3.x is installed on your system and install required Python packages.

## Running the Application
### iOS App
Select a target iOS device or simulator in Xcode and press Run.
### Python Data Processing
Execute the Python scripts periodically to update the fuel price data:
```bash
python update_fuel_prices.py
```

## Contributing
We welcome contributions to both the iOS app and the Python data processing scripts. Please refer to the CONTRIBUTING.md file for more details on how to contribute.
