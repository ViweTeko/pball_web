# Powerball Historical Draw Analyzer (Web Application)

This project represents a new, web-based iteration of the original Powerball Historical Draw Analyzer script. Built with a modern front-end and back-end architecture, it provides a user-friendly interface for inputting historical South African Powerball draw data and leverages a robust database and API for storage and analysis.

## Architecture

This web application utilizes a three-tier architecture for improved scalability, maintainability, and separation of concerns:

*   **Back-end:** Developed with **Python DRF (Django REST Framework)** to provide a powerful and efficient API.
*   **Front-end:** Built using the progressive **Vue.js** JavaScript framework for a dynamic and responsive user interface.
*   **Database:** Stores historical draw data in a reliable and feature-rich **PostgreSQL** relational database.

This architecture is chosen for its robustness, allowing for independent development of the front-end and back-end, and providing a solid foundation for future growth and features.

## Relationship to Original Project

This project builds upon the core logic of the original [Powerball Historical Draw Analyzer script](https://github.com/ViweTeko/pball/tree/main/powerball/body). While the fundamental database interactions and analysis functions are derived from the original project, this version refactors and separates the application into distinct front-end and back-end components, moving away from a monolithic structure. This allows for a web-based user interface and better management of the application's different parts.

## Key Technologies

*   **Python DRF (Django REST Framework):** Powers the back-end API. It handles receiving data from the front-end, interacting with the database, and exposing endpoints for data input and analysis.
*   **Vue.js:** Creates the interactive front-end web page. It provides the forms for users to input draw data and will display analysis results received from the back-end.
*   **PostgreSQL:** Serves as the database for storing all historical Powerball draw information. Chosen for its reliability and advanced features compared to SQLite3.

## Getting Started (Conceptual)

Setting up and running this project will involve two main parts:

1.  **Back-end Setup:**
    *   Clone the repository.
    *   Set up a Python virtual environment.
    *   Install Django, DRF, and the PostgreSQL database driver (`psycopg2`).
    *   Configure database settings to connect to your PostgreSQL instance.
    *   Run database migrations to create the necessary tables.
    *   Start the Django development server.
2.  **Front-end Setup:**
    *   Navigate to the front-end project directory.
    *   Install Node.js and npm/yarn.
    *   Install Vue.js and project dependencies.
    *   Configure the front-end to communicate with your back-end API endpoint.
    *   Start the Vue development server.

Further detailed instructions will be provided in the respective back-end and front-end subdirectories.

## Development Considerations

As this project is developed, key considerations will include:

*   **API Design:** Designing clear and efficient API endpoints for communication between the front-end and back-end.
*   **Data Validation:** Implementing robust validation on both the front-end (for user feedback) and back-end (for data integrity and security).
*   **Error Handling:** Providing clear error messages to the user and logging errors on the back-end.
*   **Deployment:** Planning for deploying both the back-end (web server) and front-end (static file hosting or separate server).

## Learning Journey

This project is a fantastic opportunity to expand your skills. While knowledge of DRF is a strong starting point, diving into Vue.js and PostgreSQL will be a key part of this journey. Your existing understanding of SQLite3 provides a solid foundation for learning PostgreSQL, as many core database concepts are transferable. Embrace the learning process and enjoy building this application!

## How to Contribute

(Placeholder for future contribution guidelines)

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
