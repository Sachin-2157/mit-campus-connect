# MIT Muzaffarpur Student Hub

## Overview

This project is a student hub web application built with React, TypeScript, Tailwind CSS, and Radix UI. It provides a centralized platform for students of MIT Muzaffarpur to access important information, connect with peers, and manage their campus life.  The application leverages the Google Gemini AI API for an intelligent chat assistant.

## Features

*   *Authentication:* Secure login and registration for students.
*   *Dashboard:* Personalized dashboard with key information and quick links.
*   *Announcements:*  A board for important campus announcements with priority levels.
*   *Chat Assistant:* AI-powered chatbot for answering student queries.
*   *Quick Actions:*  Easy access to frequently used campus resources.
*   *Mental Health Support:* Resources and links for student wellbeing.
*   *Reporting System:*  A system for reporting issues and concerns.
*   *Community Forum:* A space for students to connect and discuss topics.
*   *Admin Dashboard:* (Admin Role Only) Tools for managing announcements and content.
*   *Responsive Design:*  Optimized for various screen sizes.

## Technologies Used

*   *Vite:* Build tool for fast development.
*   *React:* JavaScript library for building user interfaces.
*   *TypeScript:* Superset of JavaScript that adds static typing.
*   *Tailwind CSS:* Utility-first CSS framework.
*   *Radix UI:*  Accessible UI primitives.
*   *shadcn/ui:* Reusable UI components.
*   *Google Gemini AI:* Large language model for the chat assistant.
*   *react-hook-form:* Form management library.
*   *react-day-picker:* Date picker component.
*   *react-resizable-panels:* Resizable panel component.
*   *sonner:*  Toast notification library.

## Getting Started

1.  *Clone the repository:*

    bash
    git clone https://github.com/Sachin-2157/mit-campus-connect
    

2.  *Install dependencies:*

    bash
    npm install
    

3.  *Set up your Gemini API Key:*

    *   Obtain an API key from [Google AI Studio](https://makersuite.google.com/app/apikey).
    *   The application prompts for the API key on first run.  It is stored locally in your browser's local storage.

4.  *Run the development server:*

    bash
    npm run dev
    

    This will start the development server and open the application in your browser.

## Environment Variables

*   *GOOGLE\_GEMINI\_API\_KEY:*  (Required) Your Google Gemini API key.  This is currently handled via local storage in the browser.

## Deployment

You can deploy this application to any static hosting provider.  Build the application using npm run build and then deploy the contents of the dist directory.

## Contributing

Contributions are welcome! Please follow these guidelines:

*   Fork the repository.
*   Create a new branch for your feature or bug fix.
*   Make your changes and commit them with descriptive messages.
*   Submit a pull request.

## License

[MIT License](LICENSE)