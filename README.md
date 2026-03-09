🍔 PolyFood – Food Ordering Mobile App

PolyFood is a mobile food ordering application that allows users to browse restaurant menus, place orders, and track deliveries in real-time. The system is designed with three main roles: Customer, Restaurant, and Driver, providing a complete food delivery workflow.

📱 Project Information

Project Name: PolyFood

Platform: Android

Programming Language: Java

Team Members: 3

Repository: https://github.com/TrungNTPH/ProjectFoodOrderingApp

Demo: 
<img width="415" height="853" alt="image" src="https://github.com/user-attachments/assets/917ef920-bf61-4bf4-a062-44dad92ce0f0" />
<img width="424" height="883" alt="image" src="https://github.com/user-attachments/assets/9310f921-c353-4c89-b8e2-21f58c47a152" />
<img width="422" height="886" alt="image" src="https://github.com/user-attachments/assets/ad1d994a-d27c-4571-8fa4-ee536bfee27e" />


🛠️ Technologies Used

Android (Java) – Mobile application development

Firebase Authentication – Secure user login and registration

Firebase Realtime Database – Real-time data storage and synchronization

Firebase Cloud Messaging (FCM) – Push notifications for order updates

Google Maps API – Navigation support for drivers

👥 System Roles
🧑 Customer

Customers can browse restaurant menus and place food orders easily.

Features:

Register and login via Firebase Authentication

Browse food menus

Add food to cart and place orders

Receive real-time order updates

Receive push notifications for order status

🍽️ Restaurant

Restaurants manage food items and process incoming orders.

Features:

Add, edit, and manage dishes

Suggest featured dishes

Receive customer orders

Update order status (preparing, ready for delivery)

🚚 Driver

Drivers handle delivery and navigation to the customer’s location.

Features:

Receive delivery orders

Pick up orders from restaurants

Open Google Maps for navigation to customer locations

Update delivery status after completing the order

⭐ Key Features
🔐 User Authentication

Secure login and registration using Firebase Authentication.

🔄 Real-time Order Tracking

Orders are synchronized in real-time using Firebase Realtime Database, allowing customers, restaurants, and drivers to see the latest order status.

🍜 Menu & Recommendations

Restaurants can:

Add and edit food items

Suggest featured dishes to be displayed on the homepage.

🔔 Push Notifications

Customers receive order updates via Firebase Cloud Messaging (FCM).

🗺️ Google Maps Integration

Drivers can open Google Maps to navigate directly to the customer's delivery location.

🗄️ Database

The application uses Firebase Realtime Database to store and synchronize data such as:

Users

Restaurants

Dishes

Orders

Order status

All updates are synchronized instantly across devices.

🚀 Installation & Setup
1. Clone the repository
git clone https://github.com/TrungNTPH/ProjectFoodOrderingApp.git
2. Open project in Android Studio

Open Android Studio

Select Open Project

Choose the cloned project folder

3. Configure Firebase

Create a Firebase project in Firebase Console

Enable:

Authentication

Realtime Database

Cloud Messaging

Download google-services.json

Place the file inside:

app/google-services.json
4. Run the application

Connect an Android device or start an emulator and run the project from Android Studio.

📸 Application Workflow

User logs in or registers.

Customer selects food and places an order.

Restaurant receives and prepares the order.

Driver picks up the order and delivers it.

Order status updates in real-time for all users.

📌 Future Improvements

Online payment integration

Order history and analytics

Rating and review system

Improved UI/UX

Location tracking for driver delivery

📄 License

This project is developed for educational purposes.
