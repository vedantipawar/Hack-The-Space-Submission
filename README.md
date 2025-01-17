# Hack-The-Space-Submission

This repository consists of our submission for Hack-The-Space Hackathon conducted by DSC UMIT, DSC RIT, DSC QU, DSC GGI.
<h2>Group Members</h2>

[Janhavi Choudhari](https://github.com/Janhavikc)   |  [Aparna Naik](https://github.com/aparna0522)   |   [Vedanti Pawar](https://github.com/vedantipawar)

<h2>Project Description</h2>
<b>Creators:</b> Trio of enthusiastic and motivated students who want to innovate and create something essential and useful for the student community!! :)

An educational website which can potentially bring changes to the current learning lifestyle of the students, with simpler and cost-effective teaching. This project is unlike traditional applications which use monolithic architecture. The distinctiveness of this application lies in the usage of microservices architecture. We have implemented three microservices namely:

1. User Microservice
2. Courses Microservice
3. Enrollment Microservice

<b>User Microservice</b> helps in registering a user into the application. It then helps the user to login into his account and have a separate session for themselves. This microservice has an independent database(in this case MongoDB Database) which is responsible for keeping the user credentials only. The password that is stored in the database is encrptyed and hence ensures the security of the users registering on the web-app.  

<b>Courses Microservice</b> helps a logged in user to enroll into a particular course. The logged in user can then learn at their own pace from the enrolled courses. A unique feature that this web-app has is that, any user is allowed to upload their own courses unlike traditional educational web applications. Any user can upload their content for other users to learn from. 

<b>Enrollment Microservice</b> will basically transfer the api request to a third party payment service and that will take care of all the payments made by the user and accordingly help in enabling the access for the particular course for the user.

<h3>Uniqueness of the Application</h3>

1. This application allows any user to upload his course so that others can learn from the same course. (User perspective)
2. This application uses Microservices architecture which makes it scalable, reliant and robust as compared to Monolithic architectured applications. (Technology perspective)

<h3>Future Work</h3>

1. Helping peers to interact with each other and resolve their doubts. They can connect with other peers who are learning the same course. 
2. Creation of discussions forum. 
3. Adding some extra features like creation of quizes for easy evaluation. 

<h3>Application Images</h3>

<h4>Landing Page Of the Application</h4>

![Landing Page](https://user-images.githubusercontent.com/63536585/115154881-c2e30e00-a09a-11eb-8ccd-eff647dd5180.png) 

<h4>Registration Page</h4>

![Registration Page](https://user-images.githubusercontent.com/36110304/115156398-b7471580-a0a1-11eb-8486-500e445e6860.png)

<h4>Login Page</h4>

![Login Page](https://user-images.githubusercontent.com/36110304/115156423-df367900-a0a1-11eb-8adf-b1347371fa93.png)

<h4>Guidelines for a User to upload a course</h4>

![Guidelines for a User to upload a course](https://user-images.githubusercontent.com/63536585/115154936-1b1a1000-a09b-11eb-8cb0-f1ae22ac3347.png) 

<h4>Insertion of a New Course</h4>

![Insertion of a New Course](https://user-images.githubusercontent.com/63536585/115154916-f58d0680-a09a-11eb-8554-fd29dbe21cfc.png) 

<h4>Insertion of weekly videos in the newly generated Course</h4>

![Insertion of weekly videos in the newly generated Course](https://user-images.githubusercontent.com/63536585/115154971-47ce2780-a09b-11eb-8697-8ec764178a6e.png) 

<h4>Skills That a student will gain after completion of that course</h4>

![skill_info](https://user-images.githubusercontent.com/63536585/115156278-1d7f6880-a0a1-11eb-8dfa-84bf15cbab31.png)

<h4>List of courses category wise</h4>

![List of courses category wise](https://user-images.githubusercontent.com/63536585/115154992-659b8c80-a09b-11eb-9d00-494ae7967ad5.png) 

<h4>Course Display</h4>

![Course Display](https://user-images.githubusercontent.com/63536585/115155031-9380d100-a09b-11eb-959d-d73213086e4e.png) 


<h3>Detailed Videos(Video length>3mins)</h3>

1. User Microservice: https://drive.google.com/file/d/1EmapTouUb0iPVfBJ29Hpdbj1iDIWY6cs/view?usp=sharing
3. Course Microservice: https://drive.google.com/file/d/1r4XZqMt-02JYuKj9Y0H3a2MFIXpIo5Tt/view?usp=sharing
4. Enrollment Microservice:

Integration of these microservices is under progress.
