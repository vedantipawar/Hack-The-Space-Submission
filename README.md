# Hack-The-Space-Submission

This repository consists of our submission for Hack-The-Space Hackathon conducted by DSC UMIT, DSC RIT, DSC QU, DSC GGI.

<h2>Project Description</h2>
<b>Creators:</b> Trio of enthusiastic and motivated students who want to innovate and create something essential and useful for the student community!! :)

An educational website which can potentially bring changes to the current learning lifestyle of the students, with simpler and cost-effective teaching. This project is being made with the help of microservices architecture. It will have 3 microservices namely:
```
1. User Microservice
2. Courses Microservice
3. Enrollment Microservice
```

<b>User Microservice</b> helps in registering a user into the application. It then helps the user to login into his account and have a separate session for themselves. This microservice has an independent database(in this case MongoDB Database) which is responsible for keeping the user credentials only. The password that is stored in the database is encrptyed and hence ensures the security of the users registering on the web-app.  

<b>Courses Microservice</b> helps a logged in user to enroll into a particular course. The logged in user can then learn at their own pace from the enrolled courses. A unique feature that this web-app has is that, any user is allowed to upload their own courses unlike traditional educational web applications. Any user can upload their content for other users to learn from. 

<b>Enrollment Microservice</b> will basically transfer the api request to a third party payment service and that will take care of all the payments made by the user and accordingly help in enabling the access for the particular course for the user.

