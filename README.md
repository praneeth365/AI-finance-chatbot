# AI-finance-chatbot
Personal Finance Chatbot ✨
A modern, intelligent personal finance chatbot built with the Gemini API to provide intelligent guidance on savings, taxes, and investments.

Overview
This project is a web-based conversational AI system that helps users with their personal finance questions. By leveraging the power of Google's Gemini API, the chatbot provides real-time, helpful responses to inquiries about budgeting, saving money, and investment strategies.

Features
Intelligent Conversational AI: Interacts with users in a natural, friendly, and helpful manner.

Finance-Specific Guidance: Trained to provide advice on a range of financial topics, including savings, taxes, and investment.

Intuitive User Interface: A clean, modern interface built with HTML and CSS for an engaging user experience.

Responsive Design: Works seamlessly on both desktop and mobile devices.

Technologies Used
Google Gemini API: The core large language model that powers the chatbot's responses.

HTML: Structures the web page content.

CSS: Styles the user interface, including the "frosted glass" effect and overall layout.

JavaScript: Manages the user interactions, handles API requests, and dynamically updates the chat interface.

Getting Started
Prerequisites
To get a copy of this project up and running on your local machine, you will need the following:

A web browser

A code editor (like VS Code)

An API key from Google AI Studio for the Gemini API.

Installation
Clone the repository:

git clone https://github.com/your-username/your-repo-name.git
Navigate to the project directory:

cd your-repo-name
Set up your API Key:

Create a config.js file in your project's root directory.

Add your Gemini API key to this file:

JavaScript

const GEMINI_API_KEY = "YOUR_API_KEY_HERE";
Note: In a production environment, you should use environment variables to secure your API key.

Usage
Open the index.html file in your web browser.

Start typing your financial questions into the chat input field.

The chatbot will provide a response based on the Gemini API.

Future Enhancements
Persistent Chat History: Implement local storage to save chat conversations across sessions.

Visualizations: Add charts or graphs to visualize budget breakdowns and spending patterns.

User Authentication: Allow users to create profiles to save personalized financial goals and data.

Integration with Financial APIs: Connect to services like Plaid or other financial data sources (with user consent) to offer real-time, personalized advice.
