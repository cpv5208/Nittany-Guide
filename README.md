Nittany Guide

Project Overview

Nittany Guide is a student-focused web application designed to help Penn State students find important campus information, resources, and university services in one convenient location. The goal of the project is to make it easier for students to navigate campus life by providing quick access to helpful information and answers to common questions.

The website uses a simple, user-friendly interface that organizes information into different sections, allowing students to find what they need without having to search through multiple websites.

Features

Ask a Question

Provides answers to frequently asked questions about Penn State.

Uses keyword matching to identify relevant questions and display helpful responses.

Directs students toward appropriate resources when additional assistance is needed.

Highlights urgent situations and provides relevant support information.

Campus Services

Displays information about important university services.

Helps students locate resources and support services available on campus.

My Resources

Organizes useful links and resources for students.

Provides convenient access to information that may be helpful throughout the academic year.

Upcoming University Events

Displays upcoming events in a card-based layout.

Organizes events into categories, including Academics, Career, Campus Life, Arts & Entertainment, Sports, and Well-being.

Allows users to filter events by category.

Loads event information from an external events.json file stored in the GitHub repository.

Technologies Used

HTML – Provides the structure and content of the website.

CSS – Controls the website's styling, layout, and responsive design.

JavaScript – Handles navigation, FAQ functionality, event filtering, and loading event information.

JSON – Stores event information in a structured format.

GitHub Pages – Hosts the website.

Project Structure

Nittany-Guide/
│
├── index.html       # Main webpage
├── events.json      # Upcoming university events data
└── README.md        # Project documentation

How to Run the Project

Download or clone this repository.

Make sure index.html and events.json are located in the same directory.

Open index.html in a web browser to view the website.

The project can also be accessed through its GitHub Pages deployment:

Open Nittany Guide

Updating University Events

Event information is stored in the events.json file. To add or update an event:

Open events.json in the GitHub repository.

Add a new event object using the existing format.

Include the event title, category, description, location, start date, end date, and event URL.

Save and commit the changes.

The website automatically loads the updated event information when the page is refreshed.

Project Goals

The main goal of Nittany Guide is to create a centralized and accessible resource for Penn State students. By combining frequently asked questions, campus services, student resources, and upcoming events, the project aims to make finding university information faster and more convenient.
