# Cafes - API Building
This Flask application provides an API to manage information about cafes and uses SQLite as the database to create, read, update, and delete cafe records.

## Concepts Utilized
- HTTP Requests (GET, POST, PUT, PATCH, DELETE)
- Postman Software
- Publishing API documentation

## API Building
![API Building Cafes](https://github.com/katmiller00/Python-Projects/assets/159479250/a3460e21-e271-4b03-aeaa-ca1caf240302)

## Prerequisites
-   Python 3.x
-   Flask
-   Flask SQLAlchemy

## Installation
1. Clone the repository and change to the project directory:

    ```bash
    git clone https://github.com/<your-username>/Python-Projects.git
    cd Python-Projects/Cafe\ \(API\)
    ```

2. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```
## Usage
1. Set up the SQLite database by running `python app.py` in the project directory.
2. Access the API routes using your preferred HTTP client.

## API Routes
1.  GET /random - Returns information about a random cafe from the database.
2.  GET /all - Returns information about all cafes in the database.
3.  GET /search - Returns information about cafes that match the specified location.
4.  POST /add - Adds a new cafe to the database.
5.  PATCH /update-price/{cafe_id} - Updates the price of a cafe with the specified ID.
6.  DELETE /report-closed/{cafe_id} - Deletes a cafe with the specified ID from the database.
