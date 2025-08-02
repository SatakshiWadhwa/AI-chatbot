Gemini Chatbot
This project is a simple, customizable web-based chatbot that uses the Google Gemini API to generate responses. It features a clean and modern chat interface and is built with HTML, CSS, and JavaScript.

Features
Interactive Chat Interface: A user-friendly chat window to send and receive messages.

Gemini API Integration: Connects to Google's Gemini API to provide intelligent and conversational responses.

Typing Indicator: Shows a typing indicator while the bot is generating a response.

Responsive Design: The layout adjusts for different screen sizes, making it usable on both desktop and mobile devices.

Easy to Customize: The code is well-commented and structured, making it easy to modify and extend.


Getting Started
Prerequisites
Before you begin, you will need to have a Google Gemini API key. You can obtain one from the Google AI Studio.

Installation
Clone the repository:

Bash

git clone https://github.com/your-username/gemini-chatbot.git
Navigate to the project directory:

Bash

cd gemini-chatbot
Add your API Key:
Open the script.js file and replace 'YOUR_API_KEY' with your actual Google Gemini API key:

JavaScript

const API_KEY = 'YOUR_API_KEY';
Open index.html in your browser:
You can now open the index.html file in your preferred web browser to start using the chatbot.

How It Works
The chatbot is built with three main files:

index.html: Provides the basic structure of the chat window.

styles.css: Defines the styling for the chat interface, including colors, fonts, and layout.

script.js: Contains the logic for handling user input, sending requests to the Gemini API, and displaying messages in the chat window.

When a user sends a message, the script.js file sends a request to the Gemini API with the user's message as the prompt. The API then returns a response, which is displayed in the chat window.

Customization
You can customize the chatbot's appearance and behavior by modifying the following files:

styles.css: Change the colors, fonts, and other visual elements to match your desired theme.

script.js:

Modify the API_URL to use a different version of the Gemini API.

Adjust the cleanMarkdown function to handle different formatting requirements.

Change the profile images for the user and the bot by updating the image paths in the addMessage function.

Contributing
Contributions are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.

# AI-chatbot
