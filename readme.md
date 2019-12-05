# Time Table Generator automation using a genetic algorithm

## Introduction
Time Table Scheduling is an NP-hard problem and hence polynomial time verifiable using genetic algorithms. It a typical scheduling problem that appears to be a tedious job in every academic institute once or twice a year. In earlier days, time table scheduling was done manually with a single person or some group involved in the task of scheduling it manually, which takes a lot of effort and time. Planning timetables is one of the most complex and error-prone applications.
Timetabling is the task of creating a timetable while satisfying some constraints. There are basically two types of constraints, soft constraints, and hard constraints. Soft constraints are those if we violate them in scheduling, the output is still valid, but hard constraints are those which if we violate them; the timetable is no longer valid. The search space of a timetabling problem is too vast, many solutions exist in the search space and few of them are not feasible. Feasible solutions here mean those which do not violate hard constraints and as well try to satisfy soft constraints. We need to choose the most appropriate one from feasible solutions. Most appropriate ones here mean those which do not violate soft constraints to a greater extent. In this project, hard-constraints have been taken care of strictly and it has been ensured that soft-constraints are as well followed as much as possible.

**Soft-constraints (flexible):**

  • The more or less equal load is given to all faculties

  • Required time (hours per week) is given to every Batch

**Hard-constraints (rigid):**

  • There should not be any single instance of a faculty taking two classes simultaneously

  • A class group must not have more than one lectures at the same time

## Getting Started

Instructions for using this project :

This project is configured in eclipse and is a simple implementation

  * Download the archived folder in the system.

  * Import the project in Eclipse ( you can even copy the package into a new project if you use a different IDE / If the import of Eclipse project doesn't work well with that IDE )

  * Import users.sql file in your database

  * Set your database credentials in UserDao.java
   
    Class.forName("com.mysql.jdbc.Driver");
    con = DriverManager.getConnection("jdbc:mysql://localhost:3306/test", "", "");
   

  * Put the input.txt file anywhere in the drive and give its location in inputdata.java.
   
    File file = new File("c:\\test\\input.txt");



## Prerequisites

  * Java 8
 
  * Eclipse(compatible with Enterprise Edition)
 
  * Tomcat (or any other) Local Server
 
  * MySql Database

## Running the tests

Click 'Get Started with us today' on the homepage

Login (username: pranav password: khurana)

Click on 'Test with custom input'

## Deployment

You need to load the required jar files to make this project run

## Built With

  * [Struts] - The web framework used
  * JSP (Java server pages).
  * Servlet
  * JavaScript
  * HTML
  * CSS
  * MySQL (database)
 

## Conclusion and Further Work

### Conclusion
The process of Time Table generation has been fully automated with this software. This web app can now cater to multiple colleges, universities and schools which can rely on it for their Time Table scheduling which earlier had to be done by hand.

### Evaluation
Using Genetics Algorithm, a number of trade-off solutions, in terms of multiple objectives of the problem, could be obtained very easily. Moreover, each of the obtained solutions has been found much better than a manually prepared solution that is in use.

### Further Work
• Though this web-app serves as a basic time table generator, there is a lot more which could be done to make this project even better in terms of consideration of soft constraints like a professor giving preference to a particular class.

• The up-gradations I look up to currently will be Classroom size considerations, lab facility consideration and multiple subject selection for faculty. I will try to bring the following up-gradations very soon.

• More features such as schedule print for individual faculty etc. would also be involved to make this more useful as a final product.


## Author

** Ishan Arora, Vikrant Singh, Akshay Gupta, Naman Deept. **
