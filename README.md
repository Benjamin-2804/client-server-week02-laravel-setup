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

The `app/` folder contains the core application code, including controllers, models, and other classes that handle the application's business logic.

routes/

The `routes/` folder stores all route definitions. These routes determine how the application responds to incoming HTTP requests and direct users to the appropriate controllers or views.

resources/

The `resources/` folder contains the application's views, language files, and frontend assets. The `views` subfolder holds Blade templates used to build the user interface.

public/

The `public/` folder is the web server's document root. It contains the `index.php` file, which serves as the application's entry point, along with publicly accessible files such as images, CSS, JavaScript, and other assets.

config/

The `config/` folder stores configuration files for the Laravel application, including settings for the database, mail services, caching, sessions, and other system components.

database/

The `database/` folder contains files related to database management, including migrations, seeders, and factories. These files are used to create, modify, and populate the application's database.

<h1>Problems Encountered</h1>

1. Laravel Installer Command Not Found

After installing Laravel, the `laravel` command was not recognized in the Command Prompt. This made it impossible to create a new Laravel project using the Laravel Installer until the installation was properly configured.



The issue was resolved by ensuring that the Laravel Installer was installed correctly through Composer and that Composer's global vendor/bin directory was added to the system's PATH environment variable. After restarting the Command Prompt, the laravel -V command successfully displayed the installed Laravel version.

2. Missing PHP Zip Extension

While creating the Laravel project, the installation failed because the required PHP Zip extension was not enabled. As a result, Composer could not extract the downloaded packages until the extension was activated.

<h1>Reflection</h1>

Completing this laboratory activity gave me a better understanding of how a Laravel development environment is set up and how client-server technologies work together in web development. Before this activity, I was only familiar with the basic concepts of PHP and web development. By installing PHP, Composer, Laravel, Git, MySQL, and Visual Studio Code, I learned the purpose of each tool and how they work together to create and manage Laravel applications.

During the installation process, I encountered several challenges, including the Laravel Installer command not being recognized, the missing PHP Zip extension, and a firewall issue that prevented access to the local development server. Although these problems were frustrating at first, troubleshooting them helped me improve my problem-solving skills. I learned the importance of reading error messages carefully, checking system configurations, and following the official documentation when resolving technical issues.

Laravel is important in client-server development because it provides a structured framework for building secure, organized, and maintainable web applications. Its built-in features, such as routing, Blade templating, and Artisan commands, make the development process faster and more efficient. I also gained a better understanding of how a client sends requests to the server and how Laravel processes those requests before returning the appropriate response.

Overall, this activity strengthened my confidence in setting up a professional development environment and using Git for version control. The knowledge and skills I gained will serve as a strong foundation for future Laravel projects and more advanced client-server applications throughout the semester.
