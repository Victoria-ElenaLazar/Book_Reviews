# Book Reviews

Welcome to Book Review Laravel application, where you can explore books and it's reviews. 

## Features

- **Browse Books:**
    - Explore a diverse collection of books.
    - Filter books by popularity and its rate.
  

- **Reviews:**
    - See what other people thing about the books.
    - Contribute to the community by sharing your opinion about the books.
  

- **Limited reviews to be added and validation of responses:**
    -  Ensuring that the customer share solid opinions about the books by limiting
      the number of reviews to 3 per hour.
    -  Make sure the opinion is described in at least 15 characters and the rating is chosen.

## Getting Started

### Prerequisites

- PHP 8.0 or later
- MySQL or another relational database
- [Composer for dependency management](https://getcomposer.org/)
- [Laravel Framework](https://laravel.com/)
- [Docker](https://www.docker.com/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Victoria-ElenaLazar/Book_Reviews.git
   cd Book_Reviews
   ```
2. **Install dependencies**: Navigate to your project root directory and install
   the required dependencies using Composer.
   ```bash
   composer install
   ```
3. **Configure environment**: Copy the .env.example file to a new file named .env and configure your database connection in the new .env file.

4. **Run Docker**: Open Docker desktop, log in, and then open the terminal in your project root directory and run the following command:
    ````
    docker-compose up -d
    ````

5. **Connection to Adminer**: Visit http://localhost:8080 in your browser to access Adminer and enter the database credentials.
6. **Create Database** In your terminal, run the following commands:
    ````
    php artisan migrate
    php artisan db:seed
    ````
    The migrate command will create the necessary database tables, and the db:seed command will seed the database with fake data.````
    php artisan migrate:refresh --seed


7. **Start Development Server**: Open the terminal in your project root directory and run the following command:

   ````
   php artisan serve
   ````
    Access the provided link in your browser. You should be redirected to the main page.

