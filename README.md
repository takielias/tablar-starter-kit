# Laravel Tablar Starter Kit

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
