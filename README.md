## Experiment 1
## Aim: Responsive Shopping Cart Web Application
## Project Overview
This is a responsive shopping cart web application built using HTML,CSS and Js.
It includes the following features: -> User Registration -> User Login -> Product Catalog -> Shopping Cart
## Features
-> Registration and Login pages with form validation -> Product catalog displaying items in a responsive grid 
-> Cart functionality to add/remove items -> Fully responsive design using CSS Flexbox and Grid
## Technologies Used
-> HTML -> CSS -> JS
## Pages
-> register.html – User registration -> login.html – User login -> catalog.html – Product listing -> cart.html – Shopping cart page
## How to Run
STEP TO RUN THE PROJECT
1.Clone the repository
2.git clone 
3.cd shopping-cart
4.Install dependencies 
5.npm install
6.Run the server
7.node server.js
8.Open the browser and visit
9.http://localhost:3000
        (OR) 
Just Go to GoLive option
License
This project is open-source and free to use.
## Output
![image](https://github.com/user-attachments/assets/9af001cc-a12a-4473-a27b-4441f258f2ec)
![image](https://github.com/user-attachments/assets/30287bd0-fb4e-4c86-a6ee-941255dde4e2)
![image](https://github.com/user-attachments/assets/5d5b75b4-8c4f-467d-90ad-42fdcfe7c73a)
![image](https://github.com/user-attachments/assets/d8e089e8-212f-4820-9f50-f86ecc7a023b)
![image](https://github.com/user-attachments/assets/a1bc9b1c-8d49-4081-8d20-db9aebaa67a5)

## Experiment 2
## Aim: Responsive Shopping Cart Web Application using Bootstrap
## Project Overview
This is a responsive shopping cart web application built using HTML,CSS,JS. The app allows users to register, log in, browse products, and manage their shopping cart.
## Features
-> User Registration and Login forms with validation -> Product Catalog using Bootstrap Grid -> Shopping Cart to add/remove items -> Fully responsive design using Bootstrap components
## Technologies Used
-> HTML -> CSS -> Bootstrap 5 -> JS
## Pages
-> register.html – User registration -> login.html – User login -> catalog.html – Product catalog with Bootstrap Cards/Grid 
-> cart.html – Shopping cart page with item management
## How to Run
Clone or download the repository.
Open any of the .html files in your browser.
Navigate through the app using the navbar or links.
            (OR) 
Just Go to GoLive option
## License
This project is open-source and free to use.
## Output
![image](https://github.com/user-attachments/assets/d6a5e778-aa9c-48c1-a99a-95b78d9ec840)
![image](https://github.com/user-attachments/assets/910efb28-ab33-4efc-b52f-e3d654197474)

## Experiment 3
## Aim: Shopping Cart Web Application with Client-Side Validation
## Project Overview
This is a responsive shopping cart web application built using HTML,CSS,JS,Bootst. It includes user registration, login, product catalog,
and a shopping cart—now enhanced with client-side validation using JS.
## Features
-> Client-side validation for registration and login forms using JavaScript -> Real-time input validation feedback (email, password, etc.)
-> Product catalog displayed using Bootstrap Cards and Grid -> Shopping cart functionality to add and remove products -> Fully responsive layout using Bootstrap
## Technologies Used
-> HTML -> CSS -> Bootstrap -> JS
## Pages
-> register.html – User registration with JavaScript validation -> login.html – User login with input checks -> catalog.html – Product listing -> cart.html – Shopping cart page
## Client-Side Validation Includes
Required field checks Valid email format Password strength rules (min length, characters) Matching confirm password Instant feedback using JavaScript
## How to Run
Download or clone the repository.
Open register.html or login.html in a browser to test validation.
Navigate through catalog and cart pages using navbar or links. (OR) Just Go to GoLive option.
## License
This project is open-source and free to use.
## Output
![image](https://github.com/user-attachments/assets/8797d1b6-08ac-4a0c-a688-a59ca92bba4a)

## Experiment 4
## Aim: Weather Info App using ES6 and OpenWeatherMap API
## Project Overview
This project demonstrates the use of ES6 features by the Weather data from OpenWeatherMap API an display the graph on this webpage.
## Features
Fetches real-time weather data** using OpenWeatherMap API Displays temperature and weather info in a graph Uses modern JS(ES6) syntax: Arrow Functions Callbacks Promises Async/Await
## Technologies Used
HTML CSS JS OpenWeatherMap API Chart.js for graph rendering
## How It Works
User enters a city name.
App fetches weather data using fetch() and async/await.
The data is displayed in a line/bar chart using Chart.js.
## Files
index.html – UI for entering city and displaying graph style.css – Basic styling script.js – JavaScript using ES6 features
## How to Use
Get a free API key from https://openweathermap.org/api
Replace "YOUR_API_KEY" in script.js with your API key.
Open index.html in a browser.
Enter a city name and view the graph.
## License
This project is open-source and free to use.
## Output
![image](https://github.com/user-attachments/assets/14754fbf-3d98-4670-b53f-9a8a3979a4d6)
![image](https://github.com/user-attachments/assets/0f0b1f22-11dc-46fc-98d5-a7926fa51c59)

## Experiment 5
## Aim: Java Standalone CRUD Application with Database
## Project Overview
This is a standalone Java application that connects to a MySQL database and performs CRUD operations (Create, Read, Update, Delete) on a database table.
## Features
Add new records View all records Update existing records Delete records Simple console-based UI using Java
## Technologies Used
JDBC (Java Database Connectivity) MySQL or Oracle Database Command-line interface
## Database Requirements
MySQL Example sql CREATE DATABASE studentdb; USE studentdb; CREATE TABLE students ( id INT PRIMARY KEY AUTO_INCREMENT, name VARCHAR(100), email VARCHAR(100), course VARCHAR(50) );
## How to Run
Install Java and MySQL.
Update DB connection details in the Java code:
String url = "jdbc:mysql://localhost:3306/studentdb"; String username = "root"; String password = "your_password"; 3. Compile and run javac CRUDApp.java java CRUDApp
## Files
CRUDApp.java – Main class with CRUD operations.
## License
This project is open-source and free to use.
## Output
![image](https://github.com/user-attachments/assets/6ebfa3b0-022f-4429-8396-b9b6d6cf2416)

## Experiment 6
## Aim: Shopping Cart App with Servlet & DB Integration
## Overview
This project adds Servlet controllers to the shopping cart app (Exp 1), enabling interaction with a MySQL (from Exp 5) for user and product data.
## Features
User Registration & Login (via Servlets)
Product & Cart Management
Database connection using JDBC
Runs on Apache Tomcat
## Tech Used
Java Servlets, JDBC
HTML, CSS, Bootstrap
MySQL or Oracle DB
Apache Tomcat
## Files
RegisterServlet.java, LoginServlet.java
ProductServlet.java, CartServlet.java
web.xml for servlet mapping
## Run Steps
Add JDBC JAR to WEB-INF/lib
## Deploy to Tomcat
Access at http://localhost:8080/YourApp/
## Output
![image](https://github.com/user-attachments/assets/884a9cc8-5fea-4640-95d8-e9d0ab7aecdf)
![image](https://github.com/user-attachments/assets/9e6d96ea-44b2-4520-8f21-e6606431859a)

## Experiment 7
## Aim: Session Tracking in Web Applications
## Overview
This project explores session tracking mechanisms like Cookies and HTTP Sessions to maintain user transaction history in a web application.
## Features
Tracks user login and actions across pages
Stores user-specific data like cart items or visit history
## Demonstrates both:
Cookies
HTTP Session (using HttpSession in Servlets)
## Tech Used
Java Servlets
HTML, CSS
Apache Tomcat
## What’s Implemented
Cookies: Store small user data on the browser HttpSession: Server-side user tracking with HttpSession object
## Files
LoginServlet.java, SessionServlet.java, LogoutServlet.java
web.xml – Servlet configuration
## Run Steps
Deploy the app on Apache Tomcat
Access login.html → Login → Navigate pages
Check how session or cookies maintain user info
## Output
![image](https://github.com/user-attachments/assets/2ce54f61-11fe-47bd-b5e5-0dae3aa9bf4b)
![image](https://github.com/user-attachments/assets/5f6b9df4-0a37-461e-bbc5-4bfbd583345c)

***Nodejs***

## Experiment 8
## Aim : Node.js Custom Server & Core Modules Demo
## Overview
This project demonstrates how to create a custom HTTP server using Node.js and explores built-in modules like os,path,and events.
## Features
Custom server using http module
Handles basic routing and file serving
Uses os to display system info
Uses path to handle file paths
Uses events to emit and listen for events
## Modules Used
http – Creates the server
os – System info (hostname, memory, CPU)
path – File path operations
events – Custom event handling
fs – Read/write files (optional)
## How to Run
Install Node.js
Save server.js
## Run
node server.js 
Visit http://localhost:3000 in browser
## Output
![image](https://github.com/user-attachments/assets/8097405f-c253-42b4-ac6f-70b127ab58e6)

## Experiment 9
## Aim: Express REST API for Student Data CRUD
## Project Overview
This is an Express.js web application that provides a REST API to perform CRUD operations on student data. You can test the API endpoints using Postman.
## Features
Create, Read, Update, Delete student records
RESTful API endpoints
JSON data format
Tested with Postman
## Technologies Used
Node.js
Express.js
Body-parser (for JSON parsing)
Nodemon (optional for development)
API Endpoints
## Method	Endpoint	Description
POST	/students	Create a new student
GET	/students	Get all students
GET	/students/:id	Get student by ID
PUT	/students/:id	Update student by ID
DELETE	/students/:id	Delete student by ID
## How to Run
Clone the repo and navigate to the project folder.
Install dependencies: npm install express body-parser
Start the server: node app.js Use Postman to test the API at http://localhost:3000
## Output
![image](https://github.com/user-attachments/assets/4859c489-17b7-48e5-84ee-a22f80930329)
{
"name": "Alice",
"age": 22,
"course": "B.Tech"
}

## Experiment 10
## Aim: Express REST API with JWT Authentication
## Overview
This is a secure Express.js REST API for performing CRUD operations on student data. It uses JWT (JSON Web Tokens) to protect authorized endpoints. API testing can be done using Postman.
## Features
JWT-based user login & token generation
Protected CRUD endpoints for student data
Token must be sent in Authorization header
## Technologies Used
Node.js, Express.js
JSON Web Token (jsonwebtoken)
Body-parser
API Endpoints
## Public
Method	Endpoint	Description
POST	/login	Get JWT token
Protected (require token)
## Method	Endpoint	Description
POST	/students	Create a student
GET	/students	Get all students
PUT	/students/:id	Update student by ID
DELETE	/students/:id	Delete student
## How to Run
Install dependencies: npm install express body-parser jsonwebtoken 2.Start the server: node app.js
Use Postman: First call /login to get the token Add Authorization: Bearer in headers for all other requests
## Output
{
"id": "1717682112345",
"name": "Alice",
"age": 22,
"course": "B.Tech"
}

## Experiment 11
## Aim: React Student Management System
## Overview
A simple React.js application for a Student Management System with pages for Registration,Login,Contact,and About. Routing is implemented using React Router.
## Features
Registration & Login Forms
Contact Page
About Page
Navigation between pages using React Router
## Technologies Used
React.js (with Create React App)
React Router DOM
CSS for basic styling
## Pages
/register – Student Registration
/login – User Login
/contact – Contact Information
/about – About the System
## How to Run
## Create the app
npx create-react-app student-management cd student-management npm install react-router-dom
Replace App.js and create pages (Register.js, Login.js, Contact.js, About.js)
## Start the app
npm start Open http://localhost:3000 in your browser
## Output
![image](https://github.com/user-attachments/assets/dc3bf859-8df6-43a3-9cc1-f0859d123e1f)

## Experiment 12
## React Weather App with Chart.js
## Overview
This React application fetches current and historical weather data from OpenWeatherMap API and displays it using Chart.js in graphical format.
## Features
Fetch current weather by city
Display weather trends (temperature, humidity, etc.)
Graphical charts using Chart.js
Uses a React service to call OpenWeatherMap API
## Technologies Used
React.js
Chart.js
Axios
OpenWeatherMap API
## Key Components
WeatherService.js – Handles API calls
WeatherChart.js – Renders charts using Chart.js
WeatherPage.js – UI for input and display
## Setup
Get a free API key from openweathermap.org
Add it in .env file:
EACT_APP_WEATHER_API_KEY=your_api_key
## How to Run
npx create-react-app react-weather-app
cd react-weather-app
npm install axios chart.js react-chartjs-2
npm start 
Then open: http://localhost:3000
## Output
![image](https://github.com/user-attachments/assets/743a32c4-b3c6-416c-9c74-b230f3fd6e6d)
![image](https://github.com/user-attachments/assets/7089c968-949b-40b5-8674-82017c7bcd8c)
![image](https://github.com/user-attachments/assets/8a9e3f74-891b-4684-900e-bc9c6e94f967)

## Experiment 13
## Aim: React TODO App
## Overview
A simple React.js TODO application to add, edit, and delete tasks. The app is built with reusable components and deployed to GitHub Pages.
## Features
Add tasks
Mark tasks as complete
Edit tasks
Delete tasks
Data saved in local state
## Technologies Used
React.js (with Create React App)
CSS for styling
GitHub Pages for deployment
## Components
TodoList.js – Displays list of todos
TodoItem.js – Represents individual task
AddTodo.js – Form to add new todo
App.js – Main container
## How to Run Locally
npx create-react-app react-todo
cd react-todo npm start
Deployment (GitHub Pages)
## Install GitHub Pages 
npm install gh-pages --save-dev In package.json, 
add: "homepage": "https://yourusername.github.io/react-todo", "scripts": { "predeploy": "npm run build", "deploy": "gh-pages -d build" } Deploy: npm run deploy
## Output
![image](https://github.com/user-attachments/assets/c9bf60a0-87a6-48b6-b9c9-62887f0a09ce)
![image](https://github.com/user-attachments/assets/38df7cd3-f69f-4b43-b3cb-a876125a633b)

## Experiment 14
## Aim:Django Student Management System
## Overview
A basic Django web application for a Student Management System with Registration,Login,Contact,and About pages. Routing is handled using Django URLs.
## Features
User Registration & Login
Contact Page
About Page
Template-based page rendering
URL routing with urls.py
## Technologies Used
Python 3.x
Django (4.x+)
HTML, CSS (Bootstrap for UI)
## Project Structure
students/ – Django app
views.py – Page logic
urls.py – App-level routing
templates/ – HTML pages
project/urls.py – Main routing
project/settings.py – Configuration
## How to Run
Create virtual env and install Django pip install django
2.Start project & app django-admin startproject student_project
cd student_project
python manage.py startapp students 
3.Run server python manage.py runserver
4.Visit http://localhost:8000
## Output
![image](https://github.com/user-attachments/assets/362674ca-5168-4081-a90c-84101c805d14)
![image](https://github.com/user-attachments/assets/dbd212eb-55c1-4ac3-a3fc-915a5d9bfa0b)
![image](https://github.com/user-attachments/assets/fd596f8a-c816-4e34-a528-769c4a225ac2)
![image](https://github.com/user-attachments/assets/bf6d2249-6831-4b0a-9985-9d4661bc88d5)
![image](https://github.com/user-attachments/assets/f1808a6b-9969-412c-a815-33476ed083cc)

## Experiment 15
## Aim: Django Weather App with Chart.js
## Overview
A Django application that fetches weather data (current and historical) from OpenWeatherMap API and displays it using Chart.js for graphical representation.
## Features
Fetch current and past weather by city
Display temperature, humidity trends using charts
API integration with OpenWeatherMap
Graphical charts using Chart.js (in templates)
## Technologies Used
Django (4.x+)
Requests (for API calls)
Chart.js (in frontend)
HTML, CSS, Bootstrap
## Key Structure
weather_app/
views.py – Fetch API data and pass to templates
urls.py – URL routing
templates/weather.html – Chart rendering
settings.py – Add app & templates setup
API Setup
Get API key from openweathermap.org
Add it in views.py or settings.py
## How to Run
pip install django requests
python manage.py runserver
Visit: http://localhost:8000/weather/
## Output
![image](https://github.com/user-attachments/assets/7806074a-efbe-40cd-ae90-d656fb839c12)

## Experiment 16
## Aim: Django TODO Application
## Overview
A basic TODO application built using the Django framework. It allows users to create, view, update, and delete tasks. The project is also deployed to GitHub.
## Features
Add new tasks
Mark tasks as completed
Edit tasks
Delete tasks
Clean routing with Django URLs
## Technologies Used
Django (4.x+)
SQLite (default DB)
HTML, CSS (Bootstrap for UI)
## Project Structure
todo_app/ – Django app
models.py – Task model
views.py – Logic for CRUD
urls.py – Routing
templates/ – HTML templates
project/urls.py – Project-level URLs
## How to Run
Install Django: pip install django
Start project and app
django-admin startproject todo_project
cd todo_project
python manage.py startapp todo_app
## Apply migrations 
python manage.py makemigrations
python manage.py migrate
## Run server
python manage.py runserver
Visit: http://localhost:8000
##GitHub Deployment
Push code to GitHub: 
git init
git remote add origin https://github.com/yourusername/django-todo-app.git 
git add .
git commit -m "Initial commit"
git push -u origin main
## Output
![image](https://github.com/user-attachments/assets/85038e82-3f78-4ceb-a8ef-d1600dfc31e1)

