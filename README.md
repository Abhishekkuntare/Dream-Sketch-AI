# Project Name

## Overview
This project is a web application that allows users to generate images based on drawings and text prompts. It utilizes a frontend built with React and a backend API for image generation.

## Features
- **Canvas Drawing:** Users can draw on a canvas.
- **Text Prompt Input:** Users can enter a text prompt for better image generation.
- **API Integration:** The application sends the drawing and text input to an API for processing.
- **Image Generation:** Displays the generated image upon successful API response.
- **Error Handling:** Handles API errors such as quota limits and unexpected failures.
- **Loading State:** Displays a loader while the request is being processed.

## Technologies Used
- **Frontend:** React, Tailwind CSS
- **Backend API:** Node.js, Express (if applicable)
- **State Management:** React Hooks
- **Canvas Manipulation:** HTML5 Canvas API

## Installation & Running the Application
Follow these steps to set up and run the application locally:

### 1. Clone the Repository
```sh

git clone <repository-url>
cd <project-folder>

2. Install Dependencies
npm i

3. Build the Application
npm run build

4. Start the Development Server
npm run dev

5. Open in Browser
Visit: http://localhost:3000


How to Use
Open the application in your browser.

Draw on the canvas or enter a text prompt.

Click the submit button to generate an image.

Wait for the response and view the generated image.

Error Handling
If you exceed the API quota, an error message will appear.

If the API is unavailable, a default error message will notify the user.

Contributing
Feel free to open issues or submit pull requests to improve the project.

