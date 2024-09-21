# Simple Money Track

Simple Money Track is a straightforward financial tracking application built with core PHP, MySQL, and JavaScript. It allows users to manage their income and expenses, providing a clear overview of their financial situation.

## Features

- User authentication and registration
- Add, edit, and delete income entries
- Add, edit, and delete expense entries
- Categorize transactions
- View financial summaries and reports
- Responsive design for mobile and desktop use

## Prerequisites

Before you begin, ensure you have met the following requirements:

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web server (e.g., Apache, Nginx)
- Modern web browser

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/simple-money-track.git
   ```

2. Navigate to the project directory:
   ```
   cd simple-money-track
   ```

3. Import the database schema:
   - Create a new MySQL database
   - Import the `database.sql` file located in the `database` folder

4. Configure the database connection:
   - Rename `config.sample.php` to `config.php`
   - Update the database credentials in `config.php`

5. Set up your web server to point to the `public` directory as the document root

## Usage

1. Access the application through your web browser
2. Register a new account or log in with existing credentials
3. Start tracking your income and expenses by adding new entries
4. View your financial summary on the dashboard
5. Generate reports to analyze your spending habits

## Contributing

Contributions to Simple Money Track are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/awesome-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some awesome feature'`)
5. Push to the branch (`git push origin feature/awesome-feature`)
6. Open a pull request

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

If you have any questions or suggestions, please open an issue on GitHub or contact the maintainer at:

youremail@example.com

Thank you for using or contributing to Simple Money Track!
