
# ImageFinder

## Overview

**ImageFinder** is a React.js-based web application that allows users to quickly discover similar images from around the web by searching with a keyword. This project leverages an external API to fetch images dynamically, providing users with the ability to customize the number of results they want to view.

## Features

- **Keyword-Based Search**: Enter a keyword to search for relevant images from the web.
- **Customizable Results Count**: Select the number of images to display (between 3 and 200).
- **Real-Time Validation**: Input validation ensures users select an appropriate number of images, with feedback provided via a Snackbar notification.
- **Responsive UI**: A modern and responsive interface designed for seamless navigation and use across devices.

## Technology Stack

- **React.js**: For building the user interface and managing state.
- **JavaScript (ES6+)**: Used for application logic and asynchronous operations.
- **CSS**: Styling for a visually appealing and responsive design.
- **Axios**: For making HTTP requests to the external image search API.

## Components

- **NavBar**: Provides navigation across different sections of the application.
- **BreadCrumb**: Allows users to input their search keywords and specify the number of images to retrieve.
- **Images**: Displays the fetched images in a clean, grid-based layout.
- **SnackBar**: Notifies users if their input is invalid or if other issues arise.

## Getting Started

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Anchal82-del/ImageFinder.git
   cd ImageFinder
   ```

2. **Install the dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm start
   ```

4. **Open the application in your browser:**

   Navigate to `http://localhost:3000` to view the app.

### Usage

## API Integration

The application uses an external image search API to fetch images based on the user's input. You can modify the API integration in the `services/api.js` file if needed.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

## Acknowledgments

- The external API used for image search.
  
