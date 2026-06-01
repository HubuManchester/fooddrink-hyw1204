# NutriBite

## Author

Student:Qianle Cheng

Module: 6G6Z0014 – Developing a Cross-Platform Mobile App

Institution: Manchester Metropolitan University

---

# Project Overview

NutriBite is a cross-platform food and nutrition management application developed using .NET MAUI and C#.

The application allows users to browse food and drink records, search nutritional information, add new food entries, and explore food details. The project also demonstrates the integration of mobile hardware features including camera access, location services, text-to-speech functionality, and vibration feedback.

The application was designed with accessibility and usability in mind and includes support for dark mode and large-text accessibility settings.

---

# Assessment Theme

Food and Drink

This application was developed according to the coursework requirements for the "Food and Drink" theme and demonstrates:

* Cross-platform mobile development
* Accessibility support
* Mobile hardware integration
* Validation and error handling
* Responsive user interface design

---

# Features Implemented

## Food Catalogue

Users can:

* Browse food records
* View nutritional summaries
* View calorie information
* Search by food name, category, and tags

---

## Add Food Records

Users can create new food entries by entering:

* Name
* Category
* Description
* Calories
* Protein
* Carbohydrates
* Fat
* Allergy information
* Tags

Input validation is applied to prevent invalid or incomplete records.

---

## Food Detail Page

The detail page provides:

* Full nutritional information
* Macronutrient summary
* Allergy information
* Accessibility-friendly content presentation
* Text-to-speech reading functionality

---

# Food Data Model

Each food record contains:

| Field        | Description             |
| ------------ | ----------------------- |
| Name         | Food name               |
| Category     | Food category           |
| Description  | Description of the food |
| Calories     | Energy value (kcal)     |
| Protein      | Protein content         |
| Carbs        | Carbohydrate content    |
| Fat          | Fat content             |
| Allergy Note | Allergy information     |
| Tags         | Search keywords         |

---

# Mobile Hardware Features

The application demonstrates several mobile hardware capabilities.

## Camera

Users can capture food photographs using the device camera.

## Location Services

Users can obtain:

* Country
* City
* Region
* Coordinates

using device geolocation services.

## Text-to-Speech

The application can read food information aloud using built-in speech synthesis.

## Vibration and Haptic Feedback

The application demonstrates device vibration and haptic feedback capabilities.

---

# Accessibility Features

The application includes several accessibility enhancements.

## Dark Mode

Users can switch between:

* Light Theme
* Dark Theme
* System Theme

## Large Text Mode

A large text option is provided to improve readability for users with visual impairments.

## Accessible Content

Food records provide accessibility-friendly summaries for assistive technologies.

---

# User Interface Design

The user interface follows a modern card-based design approach.

Key design principles include:

* Consistent navigation
* Clear typography
* High colour contrast
* Large touch targets
* Rounded card layouts
* Responsive design

The application has been customised with a modern green visual theme to improve visual consistency and user experience.

---

# Validation and Error Handling

Validation is implemented throughout the application to reduce user input errors.

Examples include:

* Required field validation
* Numeric value validation
* Empty input detection
* User-friendly validation messages

Error handling is used where hardware features and user interactions may fail.

---

# Technologies Used

## Framework

* .NET 9
* .NET MAUI

## Language

* C#

## User Interface

* XAML

## Data Handling

* JSON Serialization
* Local Mock Data Services

# Project Structure

FoodDrinkApp/

├── Models/

│ └── FoodItem.cs

├── Services/

│ ├── FoodCatalogService.cs

│ ├── SpeechService.cs

│ ├── AccessibilityService.cs

│ └── MockApiConfig.cs

├── MainPage.xaml

├── AddItemPage.xaml

├── FoodDetailPage.xaml

├── HardwarePage.xaml

├── SettingsPage.xaml

├── AppShell.xaml

└── MauiProgram.cs

# Development Plan

The initial development objectives were:

* Create a food catalogue system
* Allow users to search food items
* Display nutritional information
* Demonstrate mobile hardware integration
* Implement accessibility features
* Support multiple platforms using .NET MAUI

Additional improvements included:

* Modernised user interface
* Green themed visual redesign
* Improved accessibility support
* Enhanced validation feedback

# Installation

## Requirements

* Visual Studio 2022
* .NET 9 SDK
* .NET MAUI Workload

## Running the Application

1. Open the project in Visual Studio.
2. Restore NuGet packages.
3. Select a target platform.
4. Build the solution.
5. Run the application.

Supported platforms:

* Windows
* Android
* iOS
* Mac Catalyst

# Future Improvements

Potential future enhancements include:

* Cloud database integration
* User authentication
* Barcode scanning
* Food image recognition
* Nutrition recommendations
* Synchronisation between devices
* Online food database support

# Screenshots

Screenshots of the application can be added here:

* Main Page
* Add Food Page
* Food Detail Page
* Hardware Demonstration Page
* Settings Page

# GitHub Repository

This project was developed using GitHub version control with regular commits throughout development.

The repository contains:

* Full source code
* Project documentation
* README documentation
* Application resources

# Conclusion

NutriBite demonstrates the development of a modern cross-platform mobile application using .NET MAUI. The project combines food management functionality, accessibility support, and mobile hardware integration while maintaining a responsive and user-friendly interface.
