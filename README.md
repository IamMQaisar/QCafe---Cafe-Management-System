# QCafe - Cafe Management System

QCafe is a desktop application for managing operations in a cafe. It is built using C# in Visual Studio and utilizes MS SQL Server for database management. The system ensures security by encrypting (hashing + salting) users' credentials.

## Features

- **Login Interface**: Users can log in using their credentials. The system also provides options for guest login and password recovery.
- **Keyboard Hotkeys**: Convenient hotkeys are set up for quick data entry and navigation within the application.
- **Guest Access**: Guests are allowed to place new orders but have restricted access beyond that.
- **User Roles**: Users are categorized into 'Admin' and 'Superadmin'. Admins have full access except for the ability to delete users from the database.
- **Database Management**: Utilizes MS SQL Server to manage users and menu items tables.
- **Secure Password Storage**: User passwords are hashed and salted for enhanced security.
- **Order Management**: Options for placing orders, adding, updating, and deleting items are provided.
- **Billing**: Ability to print bills to printer or PDF with automatic addition of DATETIME stamp.
- **User Management**: Administrators can manage user accounts based on their roles.
- **Access Control**: The application displays the currently logged-in user and their access role (Admin or Superadmin) on the control panel.

## Getting Started

To get started with QCafe, follow these steps:

1. Clone the repository to your local machine.
2. Open the project in Visual Studio.
3. Set up the MS SQL Server database as per the provided schema.
4. Restore the backup file provided in the `database` directory into your SQL Server instance.
5. Compile and run the application.

## Usage

Upon running the application, users can log in using their credentials. Initially, use the provided superadmin credentials:
- Username: `MQaisar`
- Password: `Qais1099`

After logging in as a superadmin, you can add new users or delete existing users from the user management panel.

Depending on their role (Admin or Superadmin), users will have access to different functionalities within the system. Guests can place orders without logging in. Use the keyboard hotkeys for quick navigation and data entry.

## Contributing

Contributions are welcome! If you'd like to contribute to QCafe, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE).
