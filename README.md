
# Can I Has

An iOS app and widget to track daily calories burned and consumed, including macronutrient breakdowns.

## About This App
Most calorie tracking apps rely on estimated resting calories burned, which can be imprecise. *Can I Has* takes a more accurate approach by using measured calories burned from the Oura Ring, resulting in a personalized and realistic calorie budget. This budget helps users determine the calories that can be consumed daily to meet specific goals.

- **Calories Burned**: Directly measured using Oura Ring data for greater accuracy.
- **Calories and Macros Consumed**: Sourced from Apple Health, providing an integrated view of dietary intake.

## Features
- **Customizable Calorie Deficit**: Users can specify a calorie deficit to help with weight loss. By default, a 500-calorie daily deficit is applied to create a weekly deficit of 3,500 calories, which aligns with a typical goal of losing 1 lb per week.
- **Flexible Diet Options**: Users can select a high-protein diet or a high-carbohydrate diet. The high-carb option, designed for carb loading in race preparation, automatically increases the calorie budget by applying a -500 calorie deficit.
- **Macro Breakdown**: Displays percentage breakdowns for protein, fats, and carbs to support different dietary goals.

## Widget Support
Includes widget functionality for quick and easy access to calorie budgets and macronutrient breakdowns.

## Setup Instructions
1. **Configure Oura API**: Replace `<YOUR_OURA_API_TOKEN>` in `OuraAPIManager.swift` with your actual Oura API token.
2. **Build the App**: Open the project in Xcode and build for your device.

## License
This project is licensed under the MIT License.
