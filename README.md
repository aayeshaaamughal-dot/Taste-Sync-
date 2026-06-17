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
  <img width="262" height="565" alt="image" src="https://github.com/user-attachments/assets/0318861b-e906-40cc-8f83-8ada2f81f59a" />

* Recipe Details Screen
  <img width="276" height="556" alt="image" src="https://github.com/user-attachments/assets/e8099d61-64b3-49cd-968a-a7032856e881" />

* Favorites Screen
  <img width="266" height="551" alt="image" src="https://github.com/user-attachments/assets/3628a653-8e8b-4d5f-acea-2c6153c52298" />

* Meal Planner Screen
  <img width="264" height="554" alt="image" src="https://github.com/user-attachments/assets/6eb68c7a-b2b6-4913-a3d4-704ab3786635" />

* Analytics Dashboard
<img width="251" height="544" alt="image" src="https://github.com/user-attachments/assets/7b39ba95-eff3-4cda-97d1-f94d2f5785c9" />


 👩‍💻 Developed By
             Ayesha 

Flutter Developer | Computer Scienceb Student


⭐ If you found this project useful, don't forget to star the repository!
<img width="262" height="565" alt="image" src="https://github.com/user-attachments/assets/22036e7f-b447-418a-b4e9-19f354346c36" />
