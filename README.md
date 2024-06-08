# FuelFinder360

## Introduction

FuelFinder360 is a comprehensive tool designed to simplify the search for the most cost-effective fueling options. By integrating a Swift-developed iOS application with Python scripts for processing real-time data from CSV files, FuelFinder360 provides an unmatched resource for drivers. Users can explore fuel prices and find the cheapest or nearest gas stations seamlessly. The backend Python scripts ensure that the app's fuel price data remains up-to-date by parsing daily updated CSV files from authoritative sources, making FuelFinder360 a reliable companion for any driver looking to save on fuel.

## Features

- **Up-to-Date Fuel Prices:** Access the latest fuel prices for various types at nearby stations.
- **Station Locator:** Find gas stations based on price or proximity with detailed information.
- **Trip Planning:** Plan your trip by entering your destination and starting location to receive the most efficient route along with convenient refueling stops.
- **Expense Tracking:** Save and monitor your fuel expenses.
- **Data-Driven:** Utilizes Python scripts to parse and update fuel price data from CSV files.

## Coming Soon

- **Favorite Stations Notifications:** Save your favorite stations and receive daily notifications about price changes.
- **Fuel Price Graphs:** View graphs of fuel price trends to determine the best time to refuel your car.


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
We welcome contributions to both the iOS app and the Python data processing scripts. Please follow the standard GitHub pull request process to submit your contributions.
