💪 FitGem – Your Personal Fitness Companion Train. Transform. Thrive.

FitGem is an Android-based fitness application designed to help users manage their fitness journey in one place. It provides workout plans, diet tracking, BMI calculation, body measurements, fitness goals, and progress monitoring through a simple and user-friendly interface. 📱 About the Project FitGem helps users maintain their fitness activities, track their daily progress, and manage personal fitness goals. The application combines workout management, nutrition tracking, and fitness monitoring to provide a convenient fitness experience. ✨ Features

User Authentication – User registration and login.
Dashboard – View daily fitness activities and progress.
Workout Plans – Explore workout categories and exercise details.
Active Workout – Track workout sessions and completion.
Diet Tracking – Monitor daily calories and nutritional information.
BMI Calculator – Calculate and save BMI records.
Body Measurements – Record and manage body measurements.
Fitness Goals – Create and track personal fitness goals.
Progress Tracking – View fitness progress using charts.
User Profile – Manage personal profile information.
Settings – Customize themes, measurement units, reminders, and notifications. 🛠️ Technologies Used Technology Purpose Kotlin Android application development XML User interface design Android Studio Development environment Room Database Local data storage Retrofit REST API integration Gson JSON data conversion OkHttp HTTP communication MPAndroidChart Progress visualization Material Components UI components Gradle Build automation📂 Project Structure
FitGem/ │

├── app/

│ └── src/

│ └── main/

│ ├── java/com/example/fitgem/

│ │ ├── api/

│ │ ├── data/

│ │ │ ├── dao/

│ │ │ ├── database/

│ │ └── entity/

│ │ ├── model/

│ │ ├── utils/

│ │ ├── ActiveWorkoutActivity.kt

│ │ ├── BmiActivity.kt │ │ ├── DashboardActivity.kt

│ │ ├── DietActivity.kt

│ │ ├── GoalsActivity.kt

│ │ ├── LoginActivity.kt

│ │ ├── ProgressActivity.kt

│ │ ├── ProfileActivity.kt

│ │ ├── SettingsActivity.kt

│ │ └── WorkoutActivity.kt

│ │

│ └── res/

│ ├── drawable/

│ ├── layout/

│ ├── menu/

│ └── values/

│

├── gradle/

├── build.gradle.kts

├── settings.gradle.kts

└── README.md

⚙️ Installation and Setup
Follow these steps to run the FitGem application.

1. Clone the Repository
https://github.com/kchavda547/FitGem

2. Open in Android Studio
Open Android Studio.
Select Open Project.
Choose the FitGem project folder.
Wait for Gradle synchronization to complete.
3. Run the Application
Start an Android Emulator or connect an Android device.
Select the app configuration.
Click the Run ▶ button in Android Studio.
🗄️ Database FitGem uses Room Database for local data management.

The database includes the following entities:

UserEntity
WorkoutHistoryEntity
BodyMeasurementEntity
GoalEntity
BmiRecordEntity SharedPreferences is also used to manage user sessions and application settings. 🔗 API Integration The application includes Retrofit API endpoints for:
User Login
User Registration
Dashboard Data
Workout Plans
Workout History
Diet and Meal Tracking
Water Intake
Fitness Goals
BMI Records Note: The Laravel backend is configured separately and is not included in this Android project. 🎯 Project Objective The main objective of FitGem is to provide an easy-to-use fitness management application that helps users organize workouts, monitor nutrition, manage fitness goals, and visualize their progress. 🚀 Future Enhancements
Google Fit integration.
Push notifications and workout reminders.
Personalized workout recommendations.
Advanced nutrition tracking.
Cloud synchronization.
More detailed fitness analytics. 👩‍💻 Developer Project Name: FitGem Platform: Android Language: Kotlin Project Type: Fitness and Health Management Application
⭐ If you find this project useful, consider giving it a star!

FitGem – Stronger Every Day! 💚
