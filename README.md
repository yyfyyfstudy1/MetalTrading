# Comp5703-cs76-2

# Metal Trading

## Description

This repository contains the source code for a comprehensive application consisting of a SpringBoot backend, an Android mobile client, and a Vue2 admin interface.

## Components

### SpringBoot Backend

- **Requirements**: JDK 8 or higher, MySQL 8 or higher
- **Description**: The backend is built using SpringBoot, offering robust and scalable RESTful APIs. It is designed to handle requests from both the Android client and the Vue2 admin interface.

### Android Mobile Client

- **Requirements**: Android SDK 33 or higher
- **Description**: The mobile client is developed for Android devices, providing a user-friendly interface for on-the-go access to the application's features.

### Vue2 Admin Interface

- **Requirements**: Node.js 16
- **Description**: This admin interface is a web-based dashboard built with Vue2, facilitating easy management and monitoring of the application's operations.

## Installation

### Backend

1. Clone the repository.
2. Navigate to the `backend` directory.
3. Configure your database settings in `application.properties`.
4. Run `./mvnw spring-boot:run` to start the server.

### Android Client

1. Open the project in Android Studio.
2. Configure your API endpoints.
3. Build and run the application on an emulator or physical device.

### Vue2 Admin Interface

1. Navigate to the `admin` directory.
2. Run `npm install` to install dependencies.
3. Run `npm run serve` to start the development server.

## Usage

### SpringBoot Backend

- **Starting the Server**: Run the server using `./mvnw spring-boot:run`. It handles requests for product listings, transactions, real-time communication, and settings management.
- **API Endpoints**: Utilize API endpoints to manage products, process transactions, and support real-time communication between users.

### Android Mobile Client

- **Launching the App**: Open the app on your Android device. You will be prompted to log in or create a new account to access the features.
- **Posting Products**: Navigate to the 'Product list' section to list new gold and silver items for sale. Include descriptions, prices, and images.
- **Trading Products**: Browse available products and engage in transactions. Sending offer to the product or receive offer for your product.
- **Real-Time Communication**: Use the in-app messaging feature to communicate with buyers or sellers in real time.
- **Settings and Preferences**: Customize your app experience through the settings menu, including notification preferences and account management.

### Vue2 Admin Interface

- **Accessing the Dashboard**: Log in to the admin dashboard to oversee the marketplace. Use your admin credentials for access.
- **Product Management**: View, edit, or remove product listings. Ensure all listings meet the platform's standards and regulations.
- **Transaction Oversight**: Monitor ongoing transactions, manage disputes, and ensure a smooth trading experience for users.
- **User Management**: Oversee user accounts, including roles, permissions, and activity logs. Address any user-related issues.
- **Analyzing Data**: Use analytics tools to track sales trends, user engagement, and overall marketplace performance.

### General Tips

- **Help and Support**: Refer to the help section within each application component for assistance, or contact our support team for more specific inquiries.
- **Feedback**: We welcome and value user feedback. Please use the feedback feature in the app or admin interface to share your suggestions or concerns.

## Development

- Project deployment relies on AWS service components.
- For detailed deployment instructions, please see the [Deployment document](https://github.sydney.edu.au/yiyu7699/COMP5703-CS76-2/wiki/Development-document) of our Wiki.

## Project UI design
- The project UI design follows the principle of user-friendliness.
- For detailed instructions, please see the [Design wiki](https://github.sydney.edu.au/yiyu7699/COMP5703-CS76-2/wiki/Design-wiki) of our Wiki.

## Testing 
- The project underwent UTA testing, unit testing, stress testing, and integration testing.
- For detailed instructions, please see the [Testing document](https://github.sydney.edu.au/yiyu7699/COMP5703-CS76-2/wiki/Testing-Document) of our Wiki.

