# Hospital Backend Server

This repository contains the backend server for managing a hospital's data using Node.js and Express. The server provides endpoints for handling various entities such as hospital data, appointments, doctors, inventory, medical tests, and patients.

## Files and Directories

- **1_hospitalData.js**: Handles the hospital data management.
- **appointments.js**: Manages appointment-related functionalities.
- **doctors.js**: Contains routes and logic for managing doctor information.
- **inventory.js**: Manages the hospital's inventory.
- **medicalTests.js**: Handles information and actions related to medical tests.
- **patients.js**: Manages patient-related data and actions.
- **README.md**: This file.

## Getting Started

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```sh
    cd hospital-backend-server
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

### Running the Server

1. Start the server:
    ```sh
    npm start
    ```
2. The server will run on `http://localhost:3000`.

### API Endpoints

- **/hospitalData**: CRUD operations for hospital data.
- **/appointments**: CRUD operations for appointments.
- **/doctors**: CRUD operations for doctor information.
- **/inventory**: CRUD operations for inventory management.
- **/medicalTests**: CRUD operations for medical tests.
- **/patients**: CRUD operations for patient data.

### License

This project is licensed under the MIT License.
