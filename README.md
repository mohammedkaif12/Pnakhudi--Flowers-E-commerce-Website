
# Pankhudi - Flower eCommerce Website

Welcome to Pankhudi, an elegant and user-friendly eCommerce platform designed for flower enthusiasts. This project is built using PHP, HTML, CSS, and JavaScript, offering a seamless shopping experience with a robust admin panel.

## Features

### User Features
- **Browse Products**: View a wide range of flower products with detailed descriptions and high-quality images.
- **Shopping Cart**: Add, remove, and update items in the shopping cart with real-time price calculations.
- **User Authentication**: Secure user registration and login system.
- **Order Management**: Track order history and view order details.
- **Responsive Design**: Enjoy a seamless experience on both desktop and mobile devices.

### Admin Panel Features
- **Dashboard**: Get an overview of sales, orders, and website performance.
- **Product Management**: Add, edit, and delete products with ease.
- **Category Management**: Organize products into categories for better user navigation.
- **Order Management**: View and manage customer orders.
- **User Management**: Manage user accounts and roles.
- **Reports**: Generate sales reports and analytics.

## Installation

### Prerequisites
- XAMPP or WAMP server
- Web browser (Chrome, Firefox, etc.)
- Code editor (VS Code, Sublime Text, etc.)

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/pankhudi-flower-ecommerce.git
   ```

2. **Move to the Project Directory**
   ```bash
   cd pankhudi-flower-ecommerce
   ```

3. **Start the Local Server**
   - For XAMPP: Place the project folder in `htdocs`.
   - For WAMP: Place the project folder in `www`.

4. **Create a Database**
   - Open phpMyAdmin and create a new database named `pankhudi`.

5. **Import the Database**
   - Import the `pankhudi.sql` file located in the `database` folder into the `pankhudi` database.

6. **Update Database Configuration**
   - Open `config.php` and update the database credentials.
   ```php
   define('DB_SERVER', 'localhost');
   define('DB_USERNAME', 'root');
   define('DB_PASSWORD', '');
   define('DB_DATABASE', 'pankhudi');
   ```

7. **Access the Website**
   - Open your web browser and go to `http://localhost/pankhudi`.

## Usage

### User Access
- Register a new account or log in with existing credentials.
- Browse and search for flower products.
- Add products to the shopping cart and proceed to checkout.

### Admin Access
- Log in to the admin panel using admin credentials.
- Manage products, categories, orders, and users through the admin dashboard.

## Contributing
We welcome contributions to improve Pankhudi. To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


---
