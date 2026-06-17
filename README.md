🍽️ TasteSync - Smart Recipe Finder & Meal Planner

TasteSync is a Flutter-based Smart Recipe Finder & Meal Planner application that helps users discover delicious recipes, create personalized meal plans, track nutritional intake, and manage favorite recipes. The application integrates multiple APIs, supports offline functionality, and provides real-time updates using Provider state management.



✨ Features

 🔍 Smart Recipe Discovery

* Browse thousands of recipes
* Search recipes by name
* Filter recipes by category
* Filter recipes by cooking time
* Lazy loading and pagination support

📖 Detailed Recipe Information

* Recipe name
* Recipe image
* Ingredients list
* Preparation instructions
* Cooking time
* Recipe category

 🥗 Nutrition Analysis

* Calories
* Protein
* Carbohydrates
* Fat
* Additional nutritional information

 ❤️ Favorites Management

* Save favorite recipes
* Remove favorites
* View all saved recipes
* Offline access to favorites

### 📅 Meal Planner

* Create daily meal schedules
* Create weekly meal schedules
* Add recipes to meal plans
* Remove planned meals
* Persistent local storage

 📊 Analytics Dashboard

* Total recipes viewed
* Total favorite recipes
* Most selected recipe category
* Weekly meal plan summary
* Average daily calorie intake
* Interactive charts and visualizations

 📱 Offline Functionality

* Local caching using Hive
* Offline access to favorites
* Offline access to meal plans
* Automatic synchronization when internet connection is restored

 🛠️ Tech Stack

| Technology | Purpose                           |
| ---------- | --------------------------------- |
| Flutter    | Cross-platform mobile development |
| Provider   | State management                  |
| Hive       | Local database                    |
| REST APIs  | Recipe & Nutrition data           |
| HTTP       | API communication                 |
| FL Chart   | Data visualization                |



 🏗️ Architecture

lib/
├── models/
├── providers/
├── services/
├── screens/
├── widgets/
├── utils/
└── main.dart

 Providers

* RecipeProvider
* NutritionProvider
* FavoriteProvider
* MealPlanProvider
* AnalyticsProvider



🔗 API Integration

Recipe API

Provides:

* Recipe Name
* Ingredients
* Cooking Time
* Recipe Images
* Categories
* Instructions

 Nutrition API

Provides:

* Calories
* Protein
* Carbohydrates
* Fat
* Nutritional Analysis



 🚀 Getting Started

Clone Repository

git clone https://github.com/your-username/TasteSync.git

Install Dependencies

flutter pub get

 Run Application

flutter run

🎯 Learning Outcomes

This project demonstrates:

* State Management using Provider
* REST API Integration
* Local Database Management
* Offline-First Application Design
* Data Synchronization
* Flutter UI Development
* Analytics Dashboard Implementation
* Clean Architecture Principles



 📸 Screenshots

Add screenshots here:

* Home Screen
* Recipe Details Screen
* Favorites Screen
* Meal Planner Screen
* Analytics Dashboard


 👩‍💻 Developed By

Ayesha Noor

Flutter Developer | Computer Scienceb Student


⭐ If you found this project useful, don't forget to star the repository!
