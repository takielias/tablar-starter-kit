# Laravel Tablar Starter Kit

[![Latest Version](https://img.shields.io/packagist/v/takielias/tablar-starter-kit?color=blue&label=release&style=for-the-badge)](https://packagist.org/packages/takielias/tablar-starter-kit)
[![Stars](https://img.shields.io/github/stars/takielias/tablar-starter-kit?color=rgb%2806%20189%20248%29&label=stars&style=for-the-badge)](https://packagist.org/packages/takielias/tablar-starter-kit)
[![Total Downloads](https://img.shields.io/packagist/dt/takielias/tablar-starter-kit.svg?color=rgb%28249%20115%2022%29&style=for-the-badge)](https://packagist.org/packages/takielias/tablar-starter-kit)
[![Forks](https://img.shields.io/github/forks/takielias/tablar-starter-kit?color=rgb%28134%20115%2022%29&style=for-the-badge)](https://packagist.org/packages/takielias/tablar-starter-kit)
[![Issues](https://img.shields.io/github/issues/takielias/tablar-starter-kit?color=rgb%28134%20239%20128%29&style=for-the-badge)](https://packagist.org/packages/takielias/tablar-starter-kit)
[![Linkedin](https://img.shields.io/badge/-LinkedIn-black.svg?logo=linkedin&color=rgba(235%2068%2050)&style=for-the-badge)](https://linkedin.com/in/takielias)

This guide will walk you through the process of installing Laravel with the Tablar Starter Kit, a modern admin panel template based on [Tabler HTML Template](https://tabler.io/admin-template/preview) .

## Prerequisites

- PHP 8.3 or higher
- Composer
- Node.js & NPM
- Git

## Installation Steps

### 1. Install the Laravel Installer (if not already installed)

```bash
composer global require laravel/installer
```

Make sure the Composer bin directory is in your system's PATH.

### 2. Create a New Laravel Project with Tablar Starter Kit

```bash
laravel new my-project --using=takielias/tablar-starter-kit
```

This command will:
- Create a new Laravel application
- Install the Tablar Starter Kit
- Set up all necessary dependencies

### 3. Navigate to Your Project

```bash
cd demo-starter-kit
```

### 4. Configure Your Database

Edit the `.env` file and update the database connection details:

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password
```

### 5. Start the Development Server

```bash
composer run dev
```

Your application will be available at http://localhost:8000

## Features of Tablar Starter Kit

- Modern admin template based on Tabler
- Responsive design
- Dark mode support
- Ready-to-use dashboard components
- Authentication system pre-configured

## Troubleshooting

If you encounter any issues during installation:

1. Make sure your PHP version is compatible (8.3+)
2. Ensure Composer is up to date: `composer self-update`
3. Check Laravel installer version: `laravel --version`

## Additional Resources

- [Laravel Tabler](https://tablar.ebuz.xyz/)
- [Tabler HTML UI Kit](https://tabler.io/)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
