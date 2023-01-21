# ContactBook
This is a sample project for a console-based contact book application. The application uses C# and .NET Core, and utilizes a SQLite database for storage. The project is split into two main parts: the ConContactBook console application, and the libcontactmanagement library.

To run the application, you will need to have the .NET Core SDK and runtime installed on your system. You can download the SDK from the official .NET website: https://dotnet.microsoft.com/download

Once you have the SDK installed, navigate to the ConContactBook directory and run the command dotnet run to start the application. The application will prompt you with a menu of available commands:

    q - quit the application
    c - create a new contact
    u - update an existing contact
    d - delete a contact
    s - search for contacts

When creating or updating a contact, you will be prompted for the contact's name, phone number, and email. When searching for contacts, you can enter a search criteria (name, phone number, or email) and the application will display a list of matching contacts.

The libcontactmanagement library contains the business logic and data access code for the application. It uses the System.Data.SQLite library to interact with the SQLite database. The connection string for the database is defined in the App.config file in the ConContactBook project.
