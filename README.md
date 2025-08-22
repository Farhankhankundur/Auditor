CheckMate is a full-stack web application that performs a comprehensive, real-time audit of any given website. Unlike many online tools, it runs all checks directly from the local server, ensuring privacy and providing deep technical insights.

Core Features:

Multi-faceted Audit: It checks everything from DNS records and TLS/SSL certificates to security headers, performance metrics, SEO best practices, and accessibility issues.
AI-Powered Assistant: It integrates with the Google Gemini API. After an audit, an AI assistant provides a structured, expert analysis of the results and can answer follow-up questions in a conversational chat interface.
Client-Server Architecture: It consists of a Node.js/Express backend that performs the audit and AI communication, and a vanilla JavaScript frontend that provides a clean, tabbed interface for viewing the results.
How to Set Up and Run the Project
Follow these steps to get the project running on a new machine.

Step 1: Prerequisites

Ensure you have Node.js installed. You can download it from nodejs.org.
Step 2: Install Dependencies

Open your terminal in the project's root directory (a3).
Navigate into the backend folder:
Install the necessary Node.js packages:
Step 3: Set Up the Gemini API Key The AI Assistant requires a Google Gemini API key.

Go to Google AI Studio to get your API key.
In the backend folder, create a new file named .env.
Open the .env file and add the following line, replacing YOUR_API_KEY_HERE with the key you just generated:
This file keeps your secret key safe and out of your main code.
Step 4: Run the Server

Make sure you are in the backend directory in your terminal.
Start the server with the following command:
You should see a message like Server listening on port 3333.
Step 5: Use the Application

Open your web browser and navigate to http://localhost:3333.
You will see the CheckMate interface. Enter a website URL and click "Run Audit" to see it in action.
