# FairShare - Tip Calculator

FairShare is a simple iOS app designed to assist users in calculating tips and splitting bills among friends or colleagues. This README file provides an overview of the app's features, functionality, and installation instructions.

## Features

FairShare offers the following features:

- **Tip Calculation:** Users can input their bill amount and select a tip percentage to calculate the total tip amount and grand total, including the tip.
- **Split Bill:** Users can specify the number of people splitting the bill to calculate the amount each person needs to pay.
- **Easy Reset:** A reset button allows users to clear all inputs and start over.

## Screenshots

<img src="https://github.com/05Waleed/FairShare-Demo-App/assets/139551937/68b98e36-d190-468b-9356-4c8789bea2ea" alt="Simulator Screenshot - iPhone 15 Pro - 2024-05-29 at 19 49 23" width="300"/>
<img src="https://github.com/05Waleed/FairShare-Demo-App/assets/139551937/bc232c5b-0efc-4972-8635-34db77b6a3de" alt="Simulator Screenshot - iPhone 15 Pro - 2024-05-29 at 19 49 38" width="300"/>
<img src="https://github.com/05Waleed/FairShare-Demo-App/assets/139551937/28b3f44f-e6b2-41de-a8c3-a1c237314a0e" alt="Simulator Screenshot - iPhone 15 Pro - 2024-05-29 at 19 50 07" width="300"/>

## Installation

To use FairShare, follow these steps:

1. **Clone the Repository**
2. **Open in Xcode:** Open the project in Xcode by double-clicking the `FairShare.xcodeproj` file.
3. **Build and Run:** Build and run the project in the iOS Simulator or on a physical device.

## Usage

Once the app is installed and running, follow these steps to calculate tips and split bills:

1. **Enter Bill Amount:** Input the total bill amount in the provided text field.
2. **Select Tip Percentage:** Choose a tip percentage from the provided options or manually enter a custom tip percentage.
3. **Specify Number of People:** Use the stepper control to specify the number of people splitting the bill.
4. **View Results:** Click on the calculate button.
5. **Reset:** To start over, tap the reset button to clear all inputs and reset the calculations.

## MVC Pattern

FairShare follows the Model-View-Controller (MVC) architectural pattern:

- **Model:** The `TipModel` struct and `TipCalculator` struct are responsible for the business logic and data manipulation related to tip calculations.
- **View:** The `TipperView` class represents the user interface elements, including text fields, labels, and buttons, for displaying the tip calculation interface. It also handles user interactions and delegates them to the controller.
- **Controller:** The `TipperViewController` class acts as the intermediary between the model and view. It manages user inputs, calculates tips using the model, and updates the view accordingly. It also conforms to the `TipperDelegate` protocol to receive updates from the view.

## Contributing

Contributions to FairShare are welcome! If you have suggestions for improvements, bug fixes, or new features, please submit a pull request or open an issue on GitHub.

## Acknowledgements

FairShare uses the following libraries:

- **UIKit:** Apple's user interface framework for iOS app development.
- **Foundation:** Apple's core framework providing essential utilities and data types.
