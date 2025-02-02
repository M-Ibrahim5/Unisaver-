# UniSaver

UniSaver is a mobile app designed to reduce food waste on university campuses by allowing students to purchase surplus food from campus cafeterias, food vendors, restaurants, cafes, and bakeries at reduced prices. This project not only helps students save money but also supports local businesses and promotes sustainable habits.

## Introduction

The mobile application UniSaver addresses the growing problem of food waste on college campuses. By facilitating the sale of surplus food goods at significantly reduced prices, UniSaver provides a useful solution by bringing food merchants and students together. The program highlights the dual advantages of "Reduce Food Waste, Save Money." UniSaver's main objectives are to promote environmentally friendly consumption habits, assist local enterprises in the community, and increase public awareness of the negative impact that food waste has on the environment. Developed using Flutter, UniSaver boasts a user-friendly interface, ensuring seamless interactions for both food merchants and university students.

## Problem Statement

The food waste problem in Malaysia keeps getting worse, and there's still no effective solution. In universities, specific issues add to this challenge:
- Many students face financial constraints, making it challenging to afford regular meals.
- Some students are forced to skip meals due to financial limitations, negatively affecting their health.
- Excess food often ends up being discarded due to the lack of an efficient system for handling it.
- Campus restaurants struggle with surplus food without a proper platform to sell it.

## Objectives

- **Promote Sustainable Consumption:** Highlight the dual advantages of "Reduce Food Waste, Save Money."
  - **Outcome:** A highly efficient mobile app that educates students on sustainable consumption and offers a platform to buy surplus food at reduced prices.
- **Raise Awareness:** Increase awareness among university students and food merchants about the environmental impacts of food waste.
  - **Outcome:** Adoption of sustainable food consumption habits through targeted in-app educational content and marketing campaigns.
- **Reduce Food Waste:** Establish a realistic solution to connect food merchants and students for the sale of unsold food products at affordable prices.
  - **Outcome:** A notable decrease in food waste at university restaurants through a smooth connection between food merchants and students.

## Technology Used

- **Flutter:** For building the mobile application.
- **Firebase:** Used as the database.
- **Google Maps API:** For navigation features.
- **Stripe API:** For the payment gateway.

## User Features

### Customer
- **Login and Register:** Access the system.
- **Log Out:** Log out of the system.
- **Manage Profile:** Edit personal information, change passwords, and update other details.
- **View Food Details:** See details about available food items.
- **Search Food or Restaurant:** Find food items or restaurants.
- **Add to Cart:** Add items to the shopping cart.
- **Place Order:** Order food items.
- **Payment:** Process payments for orders.
- **Review and Rating:** Leave feedback and ratings for food items.
- **Track Pickup Order Time:** Track the order status and pickup time.
- **View Order History:** See past orders.
- **Favorite Food or Restaurant:** Save favorite food items or restaurants.
- **Share Food or Restaurant:** Share details about food items or restaurants on social media.
- **Cancelled Order:** Manage order cancellations.

### Restaurant Supervisor
- **Login and Register:** Access the system.
- **Log Out:** Log out of the system.
- **Manage Profile:** Edit personal information, change passwords, and update other details.
- **Manage Food Menu:** Add, update, or remove food items.
- **Manage Orders:** Handle incoming orders.
- **View Sales Report:** Access sales reports.

### Admin
- **Login:** Access the system.
- **Log Out:** Log out of the system.
- **Manage Account:** Manage user accounts.
- **Manage Customer and Restaurant:** Oversee customer and restaurant accounts.
- **View Statistical Report:** Access statistical data.
- **Manage Voucher:** Handle vouchers.

## Use Case Diagram
![design2 use case](https://github.com/user-attachments/assets/257d2fcc-088e-4910-aede-800ecde58729)

## User Interface

![Screenshot 2025-02-02 125838](https://github.com/user-attachments/assets/d6a26336-0a36-4217-8e5e-8792449b4722)

![image](https://github.com/user-attachments/assets/2a550615-bd1d-424f-a3bc-e1f6f09304bf)

![image](https://github.com/user-attachments/assets/4c34c7de-70ae-4ca9-95e2-d787378486f1)


## How to Run the Code

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/yourusername/UniSaver.git](https://github.com/M-Ibrahim5/unisaver.git)
   cd UniSaver
   ```

2. **Install Dependencies:**
   ```bash
   flutter pub get
   ```

3. **Set Up Firebase:**
   - Follow the instructions to add Firebase to your Flutter project: [Firebase Documentation](https://firebase.google.com/docs/flutter/setup)
   - Update the `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) files in your project.

4. **Configure APIs:**
   - Add your Google Maps API key and Stripe API key to the respective configuration files.

5. **Run the App:**
   ```bash
   flutter run
   ```
