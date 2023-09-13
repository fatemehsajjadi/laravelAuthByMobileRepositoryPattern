
# Laravel Authentication with Mobile Verification and Repository Pattern
![Laravel Logo](https://laravel.com/assets/img/components/logo-laravel.svg)
## Deployment


This repository provides a Laravel-based authentication system that allows users to sign up and log in using their mobile number. It includes mobile number verification using a verification code sent via SMS and follows the repository pattern for a clean and organized codebase.

Features
User registration with a mobile number and password.
Mobile number verification via SMS.
User login using mobile number and password.
Reset password functionality with SMS verification.
Repository pattern implementation for separation of concerns and maintainability.
Prerequisites
Before getting started, make sure you have the following prerequisites installed on your system:


```bash
  cp .env.example .env
  composer install
  php artisan key:generate
  php artisan migrate
  php artisan passport:install
  php artisan serve
  enjoy it!!!
```

Usage
With the application running, you can access it in your web browser:

http://localhost:8000
You can now register a user with a mobile number and password. The system will send a verification code via SMS. After entering the code, the user can log in.

Repository Pattern
The repository pattern is used in this application to separate the database logic from the controllers and provide an organized way to interact with the data.

Repositories can be found in the app/Repositories directory.
Services responsible for sending SMS and handling mobile verification are in the app/Services directory.
Contributing
Contributions are welcome! If you find any issues or have ideas for improvements, please open an issue or submit a pull request.

# License
This project is open-source and available under the MIT License.

Enjoy using this Laravel-based authentication system with mobile number verification and the repository pattern! If you have any questions or need further assistance, feel free to reach out.

## Authors

- [fatemehsajjadi](https://www.github.com/fatemehsajjadi)

Happy coding!

## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fatemeh-sadat-sajjadi/)



