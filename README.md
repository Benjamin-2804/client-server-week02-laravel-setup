# Project Title:
client-server-week02-laravel-setup

<h1>2. Brief Overview of Laravel</h1>

Laravel is a free and open-source PHP web framework that uses the MVC architecture to simplify the development of modern, secure, scalable, and maintainable web applications through features such as routing, database management, authentication, Blade templates, and the Artisan command-line tool.

<h1>2.1 Importance of Client-Server Technologies</h1>

Client-server technologies are essential in modern information systems because they facilitate efficient communication and data exchange between client devices and centralized servers, enabling the secure storage, processing, retrieval, and management of information while supporting multiple users, enhancing system performance and reliability, simplifying maintenance and updates, strengthening data security, and providing a scalable infrastructure capable of adapting to the growing technological and organizational demands of businesses and institutions.

<h1>2.2 Purpose of the Project</h1>

The main purpose of this project is to set up a Laravel development environment and gain a better understanding of how client-server architecture works in web development. Through this activity, students will learn how to install Laravel, run a local development server, explore the different folders and files in a Laravel project, and create a simple homepage. This project also helps students become familiar with the basic features and workflow of Laravel, which will serve as a starting point for developing more advanced web applications in the future.

<h1>3. Objectives</h1>

1. **To prepare a complete Laravel development setup** by installing and configuring the software and tools needed for the project, such as PHP, Composer, Laravel, Git, MySQL, and Visual Studio Code.

2. **To build and launch a basic Laravel application locally** and verify that it works properly through Laravel’s built-in development server using the `php artisan serve` command.

3. **To modify the default Laravel homepage** to present the required student details, including the name, student number, course, section, subject, and date.

4. **To practice using Git and GitHub for project management** by initializing a local repository, recording project updates, and uploading the completed Laravel application to a public GitHub repository.

5. **To document the development process clearly** by creating a README file that explains the setup and installation procedures, describes the project structure, includes relevant screenshots, and discusses the problems encountered and how they were resolved.


<h1>4. Development Environment<h1>

```text
Operating System: Windows 11
PHP Version: 8.5.0
Laravel Version: 5.31.0
Composer Version: 2.8.12
Git Version: 2.51.0.windows.1 
MySQL Version: 8.0.43
VS Code Version: 1.132.0
```

<h1>5. Installation Steps</h1>

### Step 1: PHP Installation

1. **Install PHP** on the computer and make sure it is properly configured for development.
2. **Open Visual Studio Code** and access the integrated terminal.
3. **Verify the PHP installation** by entering the following command in the terminal:
   `php -v`
4. **Check the displayed information** and confirm that the installed PHP version appears correctly, indicating that PHP has been successfully installed and recognized by the system.
5. **Capture a screenshot** of the terminal showing the PHP version.


![alt text](<Screenshots/PHP Verify.png>)


### Step 2: Composer Installation

1. **Download and install Composer** using the official Composer website and follow the installation instructions provided.
2. **Open Command Prompt** after completing the installation.
3. **Verify the Composer installation** by entering the following command:
   `composer -V`
4. **Check the command output** and confirm that the installed Composer version is displayed, indicating that the installation was completed successfully.
5. **Capture a screenshot** of the Command Prompt showing the Composer version.


![alt text](<Screenshots/Composer Verify.png>)


### Step 3: Laravel Installation

1. **Install Laravel** by preparing the system with the required Laravel development tools and dependencies.
2. **Install the Laravel Installer** through Composer by opening Command Prompt or the terminal and running the appropriate Composer command.
3. **Verify the Laravel installation** by entering the following command:
   `laravel -V`
4. **Check the displayed output** and confirm that the Laravel version appears correctly, indicating that the Laravel Installer has been successfully installed and recognized by the system.
5. **Capture a screenshot** of the terminal showing the Laravel version.

![alt text](<Screenshots/Laravel Verify.png>)


### Step 4: Git Installation

1. **Install Git** by downloading the installer and completing the installation process on the computer.
2. **Follow the installation instructions** and use the recommended settings unless specific configurations are required.
3. **Open Command Prompt** after the installation has been completed.
4. **Verify the Git installation** by entering the following command:
   `git --version`
5. **Check the command output** and confirm that the installed Git version is displayed, indicating that Git has been successfully installed and recognized by the system.
6. **Capture a screenshot** of the Command Prompt showing the Git version.

![alt text](<Screenshots/Git Verify.png>)

### Step 5: MySQL Installation

1. **Install MySQL** by downloading and setting up MySQL Server on the computer.
2. **Complete the MySQL Server installation** by following the setup instructions and configuring the required settings.
3. **Open Command Prompt** after the installation process has been completed.
4. **Verify the MySQL installation** by entering the following command:
   `mysql --version`
5. **Review the command output** and confirm that the installed MySQL version is displayed, indicating that MySQL has been successfully installed and recognized by the system.
6. **Capture a screenshot** of the Command Prompt showing the MySQL version.

![alt text](<Screenshots/MySQL Verify.png>)

### Step 6: Visual Studio Code Installation and Setup

1. **Install Visual Studio Code** by downloading the installer and completing the installation process.
2. **Follow the installation instructions** and allow Visual Studio Code to be properly installed on the computer.
3. **Launch Visual Studio Code** after the installation has been completed.
4. **Open the Laravel project folder** in Visual Studio Code to access and manage the project's files and directories.
5. **Capture a screenshot** showing the Laravel project successfully opened in Visual Studio Code.

![alt text](<Screenshots/Visual Code Studio Laravel Project.png>)

### Step 7: Creating a Laravel Project

1. **Create a new Laravel project** by preparing a dedicated location where the project files will be stored.
2. **Open Command Prompt** and navigate to the directory where you want to create the Laravel project.
3. **Create the Laravel application** by entering the following command:
   `composer create-project laravel/laravel hello-laravel`
4. **Wait for the installation to complete** and allow Composer to download and configure all the required Laravel files and dependencies.
5. **Check the project directory** and confirm that the `hello-laravel` folder has been successfully created.

![alt text](<Screenshots/Create Laravel Project Part 1.png>)


### Step 8: Running the Laravel Application

1. **Navigate to the Laravel project directory** by opening Command Prompt or the terminal and entering:
   `cd hello-laravel`
2. **Start the Laravel development server** by running the following command:
   `php artisan serve`
3. **Open a web browser** and enter the local server address:
   `http://127.0.0.1:8000`
4. **Verify that the application loads successfully** and check that the customized Laravel homepage is displayed correctly.
5. **Review the application** to ensure that all required information appears properly without errors.
6. **Capture a screenshot** of the running Laravel application.

![alt text](<Screenshots/Run Laravel.png>)

### Step 9: Modifying the Laravel Homepage

1. **Modify the Laravel homepage** by opening the appropriate view file in the Laravel project.
2. **Edit the homepage content** to replace the default page with the required student information.
3. **Add the following details** to the homepage:

   * Student Name
   * Student Number
   * Course
   * Section
   * Subject
   * Current Date
4. **Save all changes** made to the homepage file.
5. **Run the Laravel application** and open it in a web browser.
6. **Refresh the browser page** to confirm that the updated information is displayed correctly.
7. **Review the homepage** and ensure that all required details are visible and properly arranged.
8. **Capture a screenshot** of the completed homepage.


![alt text](<Screenshots/Student HomePage.png>)

<h1>6. Project Structure</h1>
<b>app/</b>

app/ – Contains the core logic of the application, including classes and components responsible for handling data, requests, business rules, and major system functions.

<b>routes/</b>

routes/ – Defines the URLs and paths that users can access and determines how the application responds to different requests.

<b>resources/</b>

resources/ – Contains the files used to build the user interface, such as Blade templates, CSS, JavaScript, and other frontend resources.

<b>public/</b>

public/ – Contains files that can be directly accessed by the browser, including the main index.php entry point, images, stylesheets, and JavaScript files.

<b>config/</b>

config/ – Stores important application settings and configurations for features such as databases, authentication, caching, and other Laravel services.

<b>database/</b>

database/ – Contains files used for managing database-related operations, including migrations, seeders, and factories for creating and organizing data.

<h1>7. Problems Encountered</h1>

1. Missing PHP Zip Extension
While installing Laravel, I encountered an error indicating that the PHP Zip extension was missing or disabled in XAMPP.

<h1>8. Solutions
To resolve the issue, I opened the php.ini configuration file located inside the XAMPP installation directory and searched for the Zip extension. I then enabled the extension by removing the semicolon (;) before the appropriate extension=zip line.

<h1>Reflection</h1>

Through this activity, I learned how to properly set up a Laravel development environment and understand how different software tools work together in web development. I learned that PHP is necessary for running Laravel, while Composer is used to install and manage Laravel and its dependencies. I also became more familiar with Visual Studio Code for writing and organizing code, MySQL for storing and managing data, and Git for tracking changes and managing project versions. More importantly, I learned that each tool has a specific purpose and that they need to be properly configured for the development process to work smoothly. Creating and running a Laravel application locally also helped me understand the basic process of developing and testing a web application.

One of the challenges I encountered during the activity was installing and configuring all the required software correctly. Some commands did not work immediately, and I had to check the installation paths, system settings, and configurations to determine what was causing the problem. I also encountered errors that I did not understand at first, which made the installation process more difficult. However, by carefully reading the error messages, researching possible solutions, and following the proper steps, I was able to overcome these problems. This experience taught me that troubleshooting, patience, and attention to detail are important skills in software development.

Laravel is important in client-server development because it provides developers with an organized framework for creating web applications that communicate between clients and servers. It includes useful features such as routing, database integration, authentication, middleware, and request handling, which reduce the amount of work required to build an application from the ground up. Its MVC architecture also helps separate the application's data, logic, and user interface, making the project easier to understand, maintain, and expand. Because of these features, Laravel allows developers to create web applications in a more structured and efficient way.

The knowledge I gained from this activity will be useful in future software development projects because I now have a better understanding of how to prepare and manage a development environment. I can apply what I learned when creating web applications, working with databases, using Git for version control, and troubleshooting technical issues. This experience also made me more comfortable with using command-line tools and understanding how different technologies work together. Overall, the activity provided me with practical experience that can serve as a foundation for developing more advanced applications and improving my skills as a future software developer.
