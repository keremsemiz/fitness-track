# Fitness Progress API

This is a FastAPI-based API for tracking fitness progress, including users' workouts and body measurements.

## Features

- **User Management**: Add and list users.
- **Workout Tracking**: Log and retrieve workout data, including exercises, sets, reps, and weights.
- **Measurement Tracking**: Log and retrieve body measurements, including weight and body fat percentage.

## Installation

### Using Poetry

1. Clone the repository:
    ```bash
    git clone https://github.com/keremsemiz/fitness-track-api.git
    cd fitness-progress-api
    ```

2. Install dependencies:
    ```bash
    poetry install
    ```

3. Run the application:
    ```bash
    poetry run uvicorn fitness_progress_api.main:app --reload
    ```

### Using Pip

1. Clone the repository:
    ```bash
    git clone https://github.com/keremsemiz/fitness-track-api.git
    cd fitness-progress-api
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:
    ```bash
    uvicorn fitness_progress_api.main:app --reload
    ```

## Usage

After starting the application, you can interact with the API at `http://127.0.0.1:8000`.

### Endpoints

- **POST /users/**: Add a new user.
- **GET /users/**: List all users.
- **POST /workouts/**: Add a new workout for a user.
- **GET /workouts/**: List all workouts.
- **POST /measurements/**: Add new body measurements for a user.
- **GET /measurements/**: List all body measurements.

You can also explore the API documentation by visiting `http://127.0.0.1:8000/docs` in your browser.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
