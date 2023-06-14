# Login and Signup REST API

This project implements a simple Login and Signup REST API using Spring Boot and H2 database.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Endpoints](#endpoints)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used

- Spring Boot
- H2 Database
- Maven

## Setup

1. Clone the repository.

2. Open the project in your preferred IDE.

3. Build the project using Maven.

4. Start the Spring Boot application.

## Endpoints

The following REST endpoints are available:

- `POST /api/signup`: Register a new user. Requires a JSON payload with `username` and `password` fields.

- `POST /api/login`: Authenticate a user. Requires a JSON payload with `username` and `password` fields.

## Usage

1. Make a `POST` request to the `/api/signup` endpoint with a JSON payload containing the `username` and `password` of the user you want to register. The API will respond with the registered user details if successful.

2. Use the registered `username` and `password` to make a `POST` request to the `/api/login` endpoint. If the credentials are correct, the API will respond with the user details and authentication token.

3. You can now use the authentication token for further authenticated requests.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the functionality, feel free to submit a pull request.

1. Fork the repository.

2. Create a new branch: `git checkout -b feature/my-feature`.

3. Commit your changes: `git commit -m 'Add some feature'`.

4. Push to the branch: `git push origin feature/my-feature`.

5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
