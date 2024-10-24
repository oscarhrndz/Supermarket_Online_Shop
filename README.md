# Supermarket Online Shop

Supermarket Online Shop is a mobile application built using Java in Android Studio, with Firebase integration for user authentication, real-time database, and cloud storage. The app is optimized for Pixel 7 Pro screen sizes and emulators.

## Features

- Firebase Authentication for user sign-in and sign-up.
- Firebase Realtime Database to manage products, categories, and offers.
- Firebase Cloud Storage for product images.
- Product search, filtering, and category browsing.
- Cart and wishlist functionality for users.
- Dynamic product listings with ratings and similar product recommendations.
- User-friendly UI, with a modern and intuitive design.

## Layouts

### 1. Intro Screen
<div align="center">
    <img src="https://i.postimg.cc/cCp7TJ65/Screenshot-20241024-101346-Supermarket-Shop-Online.jpg" alt="Intro Screen" width="300" />
    <img src="https://i.postimg.cc/4xz5Jbhn/Screenshot-20241024-101352-Supermarket-Shop-Online.jpg" alt="Main Screen" width="300" />
    <img src="https://i.postimg.cc/Bv71sXNX/Screenshot-20241024-101358-Supermarket-Shop-Online.jpg" alt="Detail Screen" width="300" />
</div>

This is the introductory screen that welcomes the user to the application. It features:
- A welcoming message and a colorful image of a person holding groceries.
- A **"Get Started"** button that leads to the sign-up process for new users.
- A link to the sign-in page for users who already have an account.

### Main Screen
The main screen of the app consists of the following elements:
- **Location**: Shows the current location of the user.
- **Search Bar**: Users can search for food, drinks, and other items in this bar.
- **Filter Button**: Located next to the search bar for easy access to product filters.
- **Offer Section**: Highlights current promotions and special offers.
- **Category Section**: Displays product categories with a horizontal list for easy browsing.
- **Best Deal Section**: Features the best deals of the day with an option to see all deals.
- **Bottom Navigation Bar**: Includes navigation icons for Explore, Cart, Wishlist, My Orders, and Profile.

### Detail Screen
This is the product detail screen where users can view more information about a selected product. Features include:
- **Product Image**: A high-resolution image of the product.
- **Price and Quantity**: Displays price per unit (e.g., $/kg) and allows users to select the quantity.
- **Product Rating**: Shows the product rating with a star system and number of reviews.
- **Description**: Provides a description of the product.
- **Similar Products**: Recommends similar products to the user.
- **Total Price**: Displays the total price based on the selected quantity.
- **Add to Cart Button**: A prominent "Add to Cart" button at the bottom of the screen.

## Technologies Used

- **Java**: The main programming language used for the application.
- **Firebase**: Used for authentication, database, and cloud storage.
  - **Firebase Authentication**: Manages user accounts and secure sign-in/sign-up.
  - **Firebase Realtime Database**: Stores and retrieves product information, categories, and offers in real-time.
  - **Firebase Cloud Storage**: Stores and manages images for the app.
- **Android Studio**: The development environment used to build the application.
- **Pixel 7 Pro Emulator**: Used for testing and optimizing the app's UI and performance.

## Setup and Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-repository/supermarket-online-shop.git
