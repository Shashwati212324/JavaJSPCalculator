# A web based Java JSP custom tag Calculator
A web based applicatino built using Java JSP, Servlets, Custom Tags and MySQL. 

It provides user authentication, session management and a responsive UI.
Basic arithmatic operations can be performed and the results are displayed using the custom JSP tag.

## Features

1 User can register and login with MySQL database.

2 Session Management to protect the calculator page.

3 Custom JSP tag to display calculation results.

4 Logout functionality to end the user session.

## Tech Stack Used

| Frontend : HTML, CSS, Bootstrap
| Backend : Java JSP, Servlets
| Database : MySQL

## How it works

#### 1 Registration: User register and create an account, the data is stored in MySQL database.
#### 2 Login: user can login via index.html and the credentials are verified in login.jsp
#### 3 Session Management: only the logged-in users can access calculator.jsp.
#### 4 Calculation: user can enter numbers and perform the arithmatic operation, the result will be displayed in result.jsp using <math:calculate> custom tag.
#### 5 Logout: ends session and redirects the user to the login page.





