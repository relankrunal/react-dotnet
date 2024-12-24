# TrainingPlatform README.md

# Training Platform

This project is a web application that combines a .NET backend with a React frontend. It serves as a platform for training purposes, providing a structured environment for learning and development.

## Project Structure

- **ClientApp**: Contains the React frontend application.
  - **src**: Source files for the React application.
    - **components**: React components for the application.
    - **services**: API service functions for making HTTP requests.
    - **index.tsx**: Entry point for the React application.
  - **package.json**: Configuration file for npm dependencies and scripts.
  - **tsconfig.json**: TypeScript configuration file.

- **Server**: Contains the .NET backend application.
  - **Controllers**: Contains controllers for handling HTTP requests.
  - **Models**: Contains model classes representing data structures.
  - **Program.cs**: Entry point for the .NET application.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the `ClientApp` directory and install the dependencies:
   ```
   cd ClientApp
   npm install
   ```

3. Navigate to the `Server` directory and restore the dependencies:
   ```
   cd ../Server
   dotnet restore
   ```

4. Run the application:
   - For the React frontend:
     ```
     cd ../ClientApp
     npm start
     ```
   - For the .NET backend:
     ```
     cd ../Server
     dotnet run
     ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features.

## License

This project is licensed under the MIT License. See the LICENSE file for details.