# Task Scheduler Application

## Overview

The **Task Scheduler** is a web application that enables users to create and manage scheduled tasks through an intuitive interface. Users can specify tasks, set a schedule in cron format, and receive notifications via email when tasks are executed. The application leverages **Node.js**, **MongoDB**, and **Nodemailer** to provide a reliable scheduling and email delivery service.

## Key Features

- **Task Management**: Add tasks with a detailed description, an email address for notifications, and a customizable schedule using cron syntax.
- **Email Notifications**: Scheduled emails are automatically sent to the specified addresses at the designated times.
- **Task Overview**: Users can view all scheduled tasks in a comprehensive list.

## Live Demo

- **Backend**: [View Backend](https://new-reminder.onrender.com)
- **Frontend**: [View Frontend](https://new-reminder.vercel.app/)

## API Documentation

### Endpoints

- **POST /api/tasks**: Schedule a new task (send an email).

  - **Request Body**:
    ```json
    {
      "task": "Task description",
      "email": "example@example.com",
      "schedule": "cron expression"
    }
    ```

- **GET /api/tasks**: Retrieve a list of all scheduled tasks.

## Project Setup Instructions

### 1. Installation

#### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/ashpatni20/TaskScheduler.git
   cd task-scheduler/backend
   ```
