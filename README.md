# E-class_webpage
E-class application. Separate login sessions for students, teachers, and admins, each with their unique features and access levels

The website provides the possibility to search and update courses of each academic semester, while, at the same time, it has complete data on student grades and statistics for both students and teachers. Based on the introductions created by the administrator regarding the courses as well as the assignment of these to the professors, the academic semester plan is formed for the members of the university. Specifically, the user through the application has the following options:
1. Log in as a guest:
• Show Course
• Course Search
2. Login as a teacher:
• Show Course
• Course Search
• Generate and Display Statistics for the Teacher
• Enter/Renew Grading Method
• Enter/Renew one or more Scores
• Finalization of Rating
• View/Export Course Score
• Export Course Student List
3. Login as a student:
• Show/Search Course
• Generate & Display Student Statistics
• Introduction of Statement of Courses
• Amendment of Statement of Courses
• Finalization of Declaration of Courses
• Show Course Rating
Login as administrator
• Perform all the above functions.

Architecture
The web application implemented follows a 3-tier architecture which is divided into the pieces of the client, the server and the database. On the web server side is Apache Server, which produces dynamic content in collaboration with the component where it is provided by the PHP interpreter. Since the use of Apache was chosen, XAMPP is also used, which is a distribution of Apache that contains MySQL, PHP which we used in our application. In addition, regarding the server implementation, PHP and JavaScript are used, i.e. languages ​​compatible with the web server. Finally, on the client side, Javascript and AJAX technology were used. Finally, the MySQL relational database was chosen for the proper implementation of the web application, while Visual Studio Code was used to write the code.
