# Project Title:
client-server-week02-laravel-setup

<h1>Brief Overview of Laravel</h1>

Laravel is a free and open-source PHP web framework that uses the MVC architecture to simplify the development of modern, secure, scalable, and maintainable web applications through features such as routing, database management, authentication, Blade templates, and the Artisan command-line tool.

<h1>Importance of Client-Server Technologies</h1>

Client-server technologies are essential in modern information systems because they facilitate efficient communication and data exchange between client devices and centralized servers, enabling the secure storage, processing, retrieval, and management of information while supporting multiple users, enhancing system performance and reliability, simplifying maintenance and updates, strengthening data security, and providing a scalable infrastructure capable of adapting to the growing technological and organizational demands of businesses and institutions.

<h1>Purpose of the Project</h1>

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

<h1>Installation Steps</h1>

Step 1: 

```text
1. Install PHP and install PHP 8.x.
2  Open Visual Code Studio.
3. Verify the installation with: php -v
4. Ensure that the installed PHP version is displayed.
5. Capture a screenshot of the successful verification.
```
![alt text](<Screenshots/PHP Verify.png>)

```text
Step 2: 
1. Install Composer from the website.
2. Open Command Prompt.
3. Verify the installation by running: composer -V
4. Confirm that the Composer version is displayed.
5. Capture a screenshot of the successful verification.
```
![alt text](<Screenshots/Composer Verify.png>)

```text
Step 3: 
1. Install Laravel 
2. Install the Laravel Installer using Composer.
3. Verify the installation by running either: laravel -V

or

4. composer global show laravel/installer
5. Confirm that the Laravel version is displayed.
6. Capture a screenshot of the successful verification.

or

7. composer global show laravel/installer
8. Confirm that the Laravel version is displayed.
9. Capture a screenshot of the successful verification.
```
![alt text](<Screenshots/Laravel Verify.png>)

```text
Step 4: 
1. Install Git
2. Download and install Git.
3. Open Command Prompt.
4. Verify the installation by running: git --version
5. Confirm that the installed Git version is displayed.
6. Capture a screenshot of the successful verification.
```
![alt text](<Screenshots/Git Verify.png>)

```text
Step 5: 
1. Install MySQL
2. Install MySQL Server.
3. Open Command Prompt.
4. Verify the installation by running: mysql --version
5. Confirm that the installed MySQL version is displayed.
6. Capture a screenshot of the successful verification.
```
![alt text](<Screenshots/MySQL Verify.png>)

```text
Step 6: 
1. Install Visual Studio Code
2. Download and install Visual Studio Code.
3. Launch Visual Studio Code.
4. Open the Laravel project folder.
5. Capture a screenshot showing the project opened in Visual Studio Code.
```
![alt text](<Screenshots/Visual Code Studio Laravel Project.png>)

```text
Step 7:
1. Create a Laravel Project
2. Open Command Prompt.
3. Create a new Laravel project using one of the following commands:
4. composer create-project laravel/laravel hello-laravel

or

5. laravel new hello-laravel
6. Wait for the installation process to complete successfully.
```

![alt text](<Screenshots/Create Laravel Project Part 1.png>)

```text
Step 8:
1. Run the Laravel Application
2. Navigate to the project directory. cd hello-laravel
3. Start the Laravel development server. php artisan serve
4. Open your web browser and visit: http://127.0.0.1:8000
5. Verify that the Laravel application loads successfully.
6. Capture a screenshot of the running application.
```
![alt text](<Screenshots/Run Laravel.png>)


```text
Step 9: 
1. Modify the Homepage
2. Edit the homepage of the Laravel application.
3. Display the following information:
4. Student Name
5. Student Number
6. Course
7. Section
8. Subject
9. Current Date
10. Save the changes.
11. Refresh the browser to verify the updated homepage.
12. Capture a screenshot of the customized homepage.
```

![alt text](<Screenshots/Student HomePage.png>)

<h1>Project Structure</h1>
app/

app/ – Contains the core logic of the application, including classes and components responsible for handling data, requests, business rules, and major system functions.

routes/

routes/ – Defines the URLs and paths that users can access and determines how the application responds to different requests.

resources/

resources/ – Contains the files used to build the user interface, such as Blade templates, CSS, JavaScript, and other frontend resources.

public/

public/ – Contains files that can be directly accessed by the browser, including the main index.php entry point, images, stylesheets, and JavaScript files.

config/

config/ – Stores important application settings and configurations for features such as databases, authentication, caching, and other Laravel services.

database/

database/ – Contains files used for managing database-related operations, including migrations, seeders, and factories for creating and organizing data.

<h1>Problems Encountered</h1>

1. Laravel Installer Command Not Found

After installing Laravel, the `laravel` command was not recognized in the Command Prompt. This made it impossible to create a new Laravel project using the Laravel Installer until the installation was properly configured.



The issue was resolved by ensuring that the Laravel Installer was installed correctly through Composer and that Composer's global vendor/bin directory was added to the system's PATH environment variable. After restarting the Command Prompt, the laravel -V command successfully displayed the installed Laravel version.

2. Missing PHP Zip Extension

While creating the Laravel project, the installation failed because the required PHP Zip extension was not enabled. As a result, Composer could not extract the downloaded packages until the extension was activated.

<h1>Reflection</h1>

## Reflection

### What Did You Learn?

Through this activity, I learned how to properly set up a development environment for Laravel and how the different software tools work together. I learned that PHP is required to run Laravel, while Composer is used to install and manage Laravel and its dependencies. I also learned how Visual Studio Code can be used to create and edit project files, MySQL can manage the application's data, and Git can be used to track changes and manage different versions of a project. Setting up Laravel also helped me understand the importance of configuring each tool correctly before beginning the actual development process. I gained a better understanding of how a Laravel project is created, launched, and tested on a local server.

### What Challenges Did You Encounter?

One of the main challenges I encountered was configuring the required software and making sure that each program was recognized correctly by the system. Some commands did not work immediately, which required me to check the installation paths and configurations. I also encountered difficulties when dealing with errors that I did not understand at first. Instead of simply reinstalling everything, I learned to read the error messages, search for possible causes, and follow troubleshooting steps. This experience showed me that patience and careful problem-solving are important skills when working with development tools.

### Why Is Laravel Important in Client-Server Development?

Laravel is important in client-server development because it provides a structured way to build applications where the client communicates with the server to request and process information. It includes features such as routing, database connectivity, authentication, middleware, and request handling, which make the development process more organized and efficient. Laravel's MVC architecture also separates the application's logic, data, and user interface, making the system easier to develop, maintain, and improve.

### How Will This Knowledge Help You in Future Software Development Projects?

The knowledge I gained from this activity will help me in future software development projects because I now have experience setting up and configuring the tools required for web development. I can apply what I learned when creating Laravel applications, connecting systems to databases, managing project versions with Git, and troubleshooting technical problems. This experience also improved my confidence in working with development environments and command-line tools. As I work on more complex projects, these skills will help me understand the development process more effectively and prepare me for working on real-world software applications.

