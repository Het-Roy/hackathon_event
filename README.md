# DevTask — Developer Task Manager

## Overview

**DevTask** is a full-stack productivity web application built using the **MERN Stack (MongoDB, Express, React, Node.js)**. It is designed specifically for developers to organize coding tasks, track learning goals, and manage project progress in a structured way.

Developers often keep tasks scattered across notes, reminders, or multiple apps. DevTask solves this problem by providing a **centralized dashboard where developers can create, manage, and track all their development-related tasks efficiently**.

The application provides a modern, responsive interface built with **React and TailwindCSS**, while **Node.js and Express** handle backend APIs and **MongoDB** stores all user and task data.

---

## Key Features

### Authentication System

* Secure **user signup and login**
* Password validation
* Protected routes for authenticated users
* Session handling using authentication tokens

### Task Management (CRUD)

Users can fully manage their development tasks:

* **Create Tasks** – Add new tasks with title, description, priority, and tech stack
* **View Tasks** – Display all tasks in a structured dashboard
* **Update Tasks** – Modify task details or update task status
* **Delete Tasks** – Remove tasks that are no longer needed

### Search Functionality

Users can quickly locate tasks using a **search bar**.
The search system dynamically filters tasks based on keywords in the task title.

### Filtering and Sorting

Tasks can be filtered and sorted based on different parameters such as:

* Task status (Completed / Pending)
* Priority level (Low / Medium / High)
* Technology stack
* Creation date


### Dashboard Analytics

The dashboard provides quick insights including:

* Total number of tasks
* Completed tasks
* Pending tasks
* High-priority tasks

This gives users a clear overview of their productivity.

### Responsive Design

The interface is fully responsive and works smoothly across:

* Desktop
* Tablet
* Mobile devices

TailwindCSS is used to ensure a clean and modern UI design.

---

## Tech Stack

### Frontend

* React
* React Router
* TailwindCSS
* Axios
* React Context API

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

---

## How It Works

1. Users create an account or log in.
2. After authentication, users are redirected to the dashboard.
3. Users can create and manage tasks related to development or learning.
4. Tasks can be searched, filtered, updated, or deleted.
5. The dashboard displays productivity insights and task statistics.

---

## Purpose of the Project

DevTask was built to demonstrate the implementation of a **complete MERN stack application**, covering essential full-stack development concepts including:

* REST API development
* Authentication systems
* Database integration
* State management
* Responsive UI development
* Performance optimization techniques like debouncing and pagination

---

## Future Improvements

Possible enhancements include:

* Task reminders and notifications
* Team collaboration features
* Calendar view for tasks
* GitHub integration for project tracking
* Progress analytics and charts

---

## Author

Developed by **Roy Het Jayeshkumar**.
