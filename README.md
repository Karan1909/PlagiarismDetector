# PlagiarismDetector (Team Project for course Managing Software Development CS5500) 

1. Clone the repository into your local system using the git clone link. 

**Intellij IDE**

1. Import the maven project from where it was downloaded. 

2. Checkout to the candidate branch

3. To get the application running , click on edit configurations...

4. Under Maven add a new configuration (say Run) 

5. Make the working directory point to cs5500-spring2018-team203

6. Change the command line description to  spring-boot:run

7. Apply the changes. Click on OK to exit the window. 

8. Now select the configuration you created earlier and click on run. 

9. Navigate to localhost:8080 on any browser. 

### Eclipse (Provided you have SpringBoot already installed in eclipse, If not, Please install SpringBoot Tool Suite or add that Plugin using Eclipse Marketplace. Eclipse does all the work for you)
1. Clone the candidate branch 
2. select Import in eclipse, select Maven Project, select Team203 Project as the project that you want to import 
3. Maven installs all the dependencies (wait for a while)
4. Right Click, Select Maven, Select Update Project to be sure that all the dependencies are loaded 
5. Right Click, Run as, Select SpringBoot Application
6  Go to localhost:8080, copycatch homepage will be displayed. 






# How it works. 

 ## Student 

**Registration**
1. To register as a student , click on register button in the login page.

2. Enter the student information and click on register 

3. Click on login to continue.. on the top 

**login** 

4. When directed to login page, enter the login information . 

5. You will be directed to the course page which will be empty for a new user.

6. Click on profile icon at the bottom to view the student's profile and add new courses using the dropdown. 

7. Once the profile is updated , click on take me to course page.

8. Select a course and you will be directed to assignment page.
 
9. Click on an assignment to upload the assignment.

10.Our application uses **git clone** links to get student submissions. Please make sure to enter the git clone link while uploading the assignment. Our application detects PYTHON file plagiarism only. 

 ## Professor

**Registration**

1. TO register a professor, you need to send the admin a registration request.
2. For doing so , navigate to the login page, click on are you a professor? link 
3. In the professor login , click on send a registration request. 
4. Fill in the registration request form and click on send. 
5. To complete the registration process, navigate to the login page. Click on are you admin? link.
6. Enter the following credentials to login as admin -- username: admin , password : admin. 
7. You will be directed to the admin profile page. 
8. Click on View users button.
9. Here you can approve/ reject the professor registration request. You can also view all the other users.

**login**

10.Once the request is approved you can navigate to the professor login page, then use the credentials you created earlier to login as professor.

11. You will be directed to the course page , which is empty for a new user.

12. Click on profile icon at the bottom to view the profile's profile and add new courses using the dropdown. 
13. Once the profile is updated , click on take me to course page.

14. Select a course to navigate to assignments page.

15. Professor can add new assignments or view the existing ones.

16. Clicking on an assignment  shows all submissions for that assignment.

17. Professor can select any number of submissions to compare for plagiarism or compare all of them.

18. When comparison is complete, view results icon appears. 

19. Clicking on this , directs the professor to the results page. An email is sent to the professor on his email ID. Percentage match is displayed on that page . A more detailed report generated by JPLAG can be viewed on clicking the VIEW report option against each submission.

--------------------------------------------------------------------------------------------------------------------------------

You can check this YouTube video (here)[https://www.youtube.com/watch?v=qi-6jTULTI0] which gives a Demo of the System 





