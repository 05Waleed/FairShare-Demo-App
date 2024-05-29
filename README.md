#FairShare - Tip Calculator

FairShare is a simple iOS app that helps users calculate tips and split bills among friends or colleagues. This README file provides an overview of the app's features, functionality, and installation instructions.

Features

FairShare offers the following features:

Tip Calculation: Users can input their bill amount and select a tip percentage to calculate the total tip amount and grand total, including the tip.
Split Bill: Users can specify the number of people splitting the bill to calculate the amount each person needs to pay.
Easy Reset: A reset button allows users to clear all inputs and start over.
Installation

To use FairShare, follow these steps:

Clone the Repository

Open in Xcode: Open the project in Xcode by double-clicking the FairShare.xcodeproj file.

Build and Run: Build and run the project in the iOS Simulator or on a physical device.

Usage

Once the app is installed and running, follow these steps to calculate tips and split bills:

Enter Bill Amount: Input the total bill amount in the provided text field.

Select Tip Percentage: Choose a tip percentage from the provided options or manually enter a custom tip percentage.

Specify Number of People: Use the stepper control to specify the number of people splitting the bill.

View Results: Click on calculate button

Reset: To start over, tap the reset button to clear all inputs and reset the calculations.

MVC Pattern

FairShare follows the Model-View-Controller (MVC) architectural pattern:

Model: The TipModel struct and TipCalculator struct are responsible for the business logic and data manipulation related to tip calculations.

View: The TipperView class represents the user interface elements, including text fields, labels, and buttons, for displaying the tip calculation interface. It also handles user interactions and delegates them to the controller.

Controller: The TipperViewController class acts as the intermediary between the model and view. It manages user inputs, calculates tips using the model, and updates the view accordingly. It also conforms to the TipperDelegate protocol to receive updates from the view.

Contributing

Contributions to FairShare are welcome! If you have suggestions for improvements, bug fixes, or new features, please submit a pull request or open an issue on GitHub.

Acknowledgements

FairShare uses the following libraries:

UIKit: Apple's user interface framework for iOS app development.
Foundation: Apple's core framework providing essential utilities and data types.
