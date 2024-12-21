# E Service Project

A modern web application built with **Laravel** and **Inertia.js** for creating single-page applications (SPAs) with server-side rendering and a seamless developer experience.

---

## 🚀 Features

- **Laravel**: Backend framework for building robust web applications.
- **Inertia.js**: SPA framework that provides a modern development experience without needing an API.
- **React** frontends.
- **TypeScript** for code structure
- Pre-configured with:
  - User authentication
  - Tailwind CSS for styling
  - MySQL Database
  - With full security



---

## 🛠️ Installation

Follow these steps to set up the project:

### Clone the Repository

```bash
# Clone the repository
git clone https://github.com/rajibofficial1999/e-service.ergit
cd e-service
```

### Install Dependencies

```bash
# Install PHP dependencies using Composer
composer install

# Install JavaScript dependencies using npm
npm install
```

### Set Up the Environment

1. Copy the `.env.example` file to `.env`:

   ```bash
   cp .env.example .env
   ```

2. Configure the `.env` file with your database, cache, and mail settings.

3. Generate the application key:

   ```bash
   php artisan key:generate
   ```

### Run Database Migrations

```bash
php artisan migrate --seed
```

### Run the Development Server

```bash
# Run the Laravel backend
php artisan serve

# Run the Vite development server
npm run dev
```

Visit the application at `http://localhost:8000`.

## ✨ Key Features

- **Authentication**: Pre-configured login and registration system.
- **Routing**: Seamless server-side routing with Inertia.js.
- **Frontend Framework**: Easily switch between React.
- **Responsive Design**: Built with Tailwind CSS for modern, mobile-first designs.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests. Please ensure all tests pass before submitting.

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📧 Contact

For questions or support, reach out to:

- Email: [rajibofficial1999@gmail.com](mailto\:rajibofficial1999@gmail.com)
- GitHub: [Visit GitHub](https://github.com/rajibofficial1999)

---

