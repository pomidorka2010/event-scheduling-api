# Event Scheduling API

## Overview
Event Scheduling API is a backend solution designed to facilitate the management of events. Users can schedule events, set reminders, and even integrate with popular calendar services to keep their agendas organized.

## Features
- **User Authentication**: Secure user accounts with JWT authentication.
- **Create Events**: Users can create and save events with details such as title, date, time, and location.
- **Update and Delete Events**: Modify existing events or remove them as needed.
- **Reminder Notifications**: Set reminders for upcoming events via email notification.
- **Calendar Integration**: Sync events with Google Calendar and other calendar services.

## Technologies Used
- Node.js
- Express.js
- MongoDB
- JWT for authentication
- Nodemailer for email notifications

## Getting Started
1. Clone the repo: `git clone https://github.com/yourusername/event-scheduling-api`
2. Navigate to the project directory:
   ```bash
   cd event-scheduling-api
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Create a `.env` file and set up environment variables for database connection and email service.
5. Start the server:
   ```bash
   npm start
   ```
6. Access the API via `http://localhost:3000`

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
