# Laravel Full-Stack Application

This is a full-stack Laravel application that demonstrates CRUD (Create, Read, Update, Delete) functionalities. It provides a basic template to get you started with building a Laravel application with a database backend.

## Features

-   Create new records
-   Read existing records
-   Update existing records
-   Delete records

## Requirements

-   PHP >= 8.0
-   Composer
-   Laravel >= 9.x
-   MySQL or any other supported database management system

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/hiromero/Laravel9-I.git
    ```

2. Navigate to the project directory:

    ```
    cd your-repo
    ```

3. Install dependencies:

    ```
    composer install
    ```

4. Create a copy of the `.env.example` file and rename it to `.env`:

    ```
    cp .env.example .env
    ```

5. Generate an application key:

    ```
    php artisan key:generate
    ```

6. Configure your database settings in the `.env` file:

    ```
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your_database_name
    DB_USERNAME=your_database_user
    DB_PASSWORD=your_database_password
    ```

7. Run the database migrations:

    ```
    php artisan migrate
    ```

8. Start the development server:

    ```
    php artisan serve
    ```

9. Open your web browser and visit `http://localhost:8000` to see the application in action.

## Usage

-   Create a new record: Click on the "Create" button and fill in the required information in the form.
-   Read existing records: The application displays a list of existing records on the homepage.
-   Update an existing record: Click on the "Edit" button next to a record and update the information in the form.
-   Delete a record: Click on the "Delete" button next to a record to remove it from the database.

Feel free to customize the application according to your specific requirements. Happy coding!

## License

This project is licensed under the [MIT License](LICENSE).
