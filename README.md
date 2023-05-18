# ShortCutify - Real-time Shortcut Management App with GraphQL and SSE

## Overview
ShortCutify is a real-time shortcut management application built with GraphQL and Server-Sent Events (SSE). It allows users to register, create, edit, and delete shortcuts, while providing real-time updates to the web page without the need for manual refreshing. The application implements features such as authentication, access control, metrics, response times, error handling, and evaluation.

## Problem
The problem addressed by ShortCutify is the need for a seamless and efficient way to manage and access shortcuts. Traditional approaches often require manual page refreshes or rely on outdated data, leading to a suboptimal user experience. ShortCutify solves this problem by leveraging GraphQL for efficient data fetching and SSE for real-time updates.

## Features
- **User Authentication**: Users can register and log in to their accounts, ensuring secure access to the application.
- **Shortcut Management**: Users can create, edit, and delete shortcuts as per their requirements.
- **URL Validation**: The application performs validation on URLs provided during shortcut creation to ensure data integrity.
- **Real-time Updates**: When a shortcut is updated or deleted, the corresponding item on the web page is automatically updated or removed without requiring a manual refresh.
- **Envelop Plugins**: The application can be extended using Envelop plugins to add additional functionalities and integrations.
- **Access Control**: Access control mechanisms are implemented to ensure that users can only interact with their own shortcuts.
- **Metrics**: Metrics such as response times of queries, success/error rates of queries, and other relevant statistics are collected to monitor the application's performance.
- **Error Handling**: Robust error handling mechanisms are in place to gracefully handle and report errors to users.
- **Evaluation Project**: The project serves as a real-time application built with GraphQL and SSE, demonstrating the use of these technologies in a practical scenario.

## Setup
To set up and run the ShortCutify application, follow these steps:

1. **Clone the repository**: Clone the project repository from GitHub: `git clone https://github.com/your-username/shortcutify.git`.

2. **Install dependencies**: Navigate to the project directory and install the required dependencies by running `npm install`.

3. **Configure environment variables**: Set up the required environment variables for the application, including database connection details, authentication secrets, and any other necessary configurations. Refer to the provided `.env.example` file for guidance.

4. **Start the GraphQL server**: Run the command `npm start` to start the GraphQL server. Ensure that the server is running and accessible.

5. **Start the SSE server**: Run the command `npm run sse` to start the SSE server. This server will handle real-time updates and push notifications to connected clients.

6. **Access the application**: Open a web browser and navigate to the appropriate URL to access the ShortCutify application. Register a user account, log in, and start managing your shortcuts in real-time.

## Contributing
Contributions to the ShortCutify project are welcome! If you have any ideas, improvements, or bug fixes, please submit them as issues or pull requests on the project's GitHub repository.

## License
The ShortCutify project is released under the [MIT License](LICENSE).

## Disclaimer
The ShortCutify project is provided as-is without any warranty. Use it at your own risk. The authors and contributors are not responsible for any damages or consequences that may arise from using this project.

## Contact
For any questions, suggestions, or support, you can reach out to the project maintainer at [ping me](mailto:automationtest5926@gmail.com).
