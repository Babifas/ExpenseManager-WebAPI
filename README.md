# Expense Manager

Expense Manager is a web-based application built with ASP.NET Web API, ADO.NET (disconnected architecture), and MS SQL Server, designed to help users manage their expenses efficiently.

## Features

- **Expense Management**: Allows users to add, view, update, and delete expenses.
- **Categories**: Organize expenses into different categories for better tracking.
- **Authentication**: Secure user authentication system to protect user data.
- **Validation**: Implements robust validation to ensure data integrity.
- **Disconnected Architecture**: Utilizes ADO.NET disconnected architecture for efficient data handling.
- **Scalable**: Designed with scalability in mind to accommodate future expansion.
- **RESTful API**: Provides a RESTful API for seamless integration with other systems.

## Installation

1. **Clone the Repository**: 
    ```
    git clone https://github.com/Babifas/ExpenseManager-WebAPI.git
    ```

2. **Set up Database**:
    - Create a new MS SQL Server database.
    - Execute the SQL scripts provided in the `database` directory to create the necessary tables and schema.

3. **Configure Connection String**:
    - Update the connection string in `Web.config` to point to your SQL Server database.

4. **Build and Run**:
    - Open the solution in Visual Studio.
    - Build the solution and run the application.

5. **Access the Application**:
    - Access the application through your web browser at the specified URL.

## Usage

- Register for a new account or log in if you already have an account.
- Add, view, update, or delete expenses from the dashboard.
- Organize expenses into different categories for better management.
- Securely log out after your session.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/my-feature`).
3. Commit your changes (`git commit -am 'Add my feature'`).
4. Push to the branch (`git push origin feature/my-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or feedback, please contact [babifasp@gmail.com](mailto:babifasp@gmail.com).

