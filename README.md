# knowledge_test_WebForm
# Driving Knowledge Test Website Project

This project is a Driving Knowledge Test Website built using Visual Studio. It includes master and child pages and utilizes features such as the web site project, master pages, child pages, and more. The login page serves as the start page for the website.

## Launching the Project on Visual Studio

1. Open Visual Studio.
2. Click on "File" in the menu bar and select "Open" > "Website/Solution."
3. Navigate to the project directory and select the solution file (`.sln`) or the website project folder.
4. Click "Open" to open the project in Visual Studio.

## Using Visual Studio Features

- Web Site Project: The project structure follows the Web Site Project format in Visual Studio, where you can add and manage different web pages and assets.
- Master Pages: The `MasterPage.master` file serves as the master page template for the website. It defines the common layout and elements shared across multiple pages.
- Child Pages: Each child page, such as `testtype.aspx`, `testmasterlist.aspx`, etc., inherits from the master page and extends it with specific content for that page.
- IIS (Internet Information Services): Visual Studio includes the development server for hosting and running the website during development. You can run the website directly from Visual Studio using the built-in web server.

## How the Program Works

- Login Page: The login page is the starting point of the website. Users can log in using their credentials to access the website's features.
- Dashboard: Upon successful login, users are redirected to the dashboard page, which provides an overview of the driving knowledge test.
- Test Type: The `testtype.aspx` page displays the available test types, such as Class 5 or Class 7, along with their associated information.
- Test Master List: The `testmasterlist.aspx` page shows the list of test questions, including the question, options, correct answer, and other details.
- Allocate Test: The `allocatetest.aspx` page allows the allocation of tests to specific users and test types.
- User List: The `userlist.aspx` page provides a list of registered users along with their details.
- Reports: The `reports.aspx` page allows users to generate reports and view test-related data.
- Logout: The `logout.aspx` page allows users to log out of the website.

## Getting Started

1. Clone or download the project files to your local machine.
2. Launch Visual Studio and open the project by following the instructions mentioned above.
3. Build and run the project using the debugging options in Visual Studio.
4. The website will open in your default web browser, starting with the login page.
5. Log in with valid credentials to access the website's features.

Note: This project may require additional configurations or dependencies, such as a database connection, to function correctly. Make sure to set up any necessary prerequisites based on the project's requirements.

---

This README provides an overview of the Driving Knowledge Test Website Project and explains how to launch it in Visual Studio. It also describes the usage of Visual Studio features, the structure of the program, and how to get started with the project.

