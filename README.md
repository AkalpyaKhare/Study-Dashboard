# Study Productivity Dashboard

## Overview

The Study Productivity Dashboard is a personal web-based productivity application designed to help students organize their study activities, set daily goals, manage tasks, and monitor study sessions.

The project is developed using HTML, CSS, and JavaScript. It uses browser local storage to maintain user preferences and study-related information across different pages.

## Features

### Personalized Welcome Page

The application begins with a welcome page where the user enters their name. The application also generates a greeting based on the current time of day.

### Study Goals

Users can set a daily study goal in hours. The selected goal is stored locally and displayed on the dashboard.

### Study Dashboard

The dashboard provides an overview of the user's study activities, including:

* Today's study time
* Total study time
* Daily study goal
* Daily tasks
* Study timer

### Task Management

Users can add study-related tasks to their daily task list and remove tasks when they are no longer required.

### Study Timer

The dashboard includes a study timer with controls to:

* Start the timer
* Pause the timer
* Reset the timer

### Study History

A separate history page is included for viewing previously recorded study sessions.

### Local Storage

The project uses JavaScript `localStorage` to store information such as:

* User name
* Time-based greeting
* Daily study goal
* Study history
* Other user-specific data

This allows information to remain available when navigating between pages or reopening the browser.

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Browser Local Storage

## Project Structure

```text
study-dashboard/
│
├── welcome.html
├── goals.html
├── dashboard.html
├── history.html
└── README.md
```

## How to Run the Project

1. Clone the repository.

```bash
git clone https://github.com/YOUR-USERNAME/study-dashboard.git
```

2. Navigate to the project directory.

```bash
cd study-dashboard
```

3. Open `welcome.html` in a web browser.

4. Enter your name and set your daily study goal.

5. Use the dashboard to manage tasks and track study sessions.

## Learning Outcomes

This project was developed to strengthen fundamental frontend development skills. Through this project, the following concepts were practiced:

* HTML page structure
* CSS styling and layout
* CSS Grid and Flexbox
* JavaScript functions
* DOM manipulation
* Event handling
* Timers using `setInterval()`
* Browser local storage
* Navigation between multiple HTML pages
* Basic responsive web design

## Future Improvements

The project can be further developed by adding:

* Weekly and monthly study analytics
* Graphs and progress visualizations
* Dark mode
* Task editing and completion status
* Custom study session durations
* Improved mobile responsiveness
* React-based frontend
* User authentication
* Backend integration
* Database support

## Purpose

The primary purpose of this project is to build a practical study management tool while strengthening the fundamentals of frontend web development through hands-on implementation.
