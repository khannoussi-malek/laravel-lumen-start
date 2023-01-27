# Lumen PHP Framework


This is a basic Lumen Laravel project that includes an implementation of JSON Web Token (JWT) authentication.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- PHP 7.4 or higher
- Composer
- MySQL

### Installation

1. Clone the repository
```
git clone https://github.com/khannoussi-malek/laravel-lumen-start/
```
2. Install dependencies
```
composer install
```

3. Create a copy of the .env file

 ```
 cp .env.example .env
 ```
4. Update the .env file with your database credentials
5. Run the migration
 ```
php artisan migrate
 ```

 ### Usage

To start the development server:
 ```
php -S localhost:8000 -t public
 ```
 
### Blog
For more detailed information and instructions, please refer to the [accompanying blog post](https://www.malekkhannoussi.me/blog/php/Lumen)

### Authors
- [Malek Khannoussi](https://www.malekkhannoussi.me/)
