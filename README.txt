# SetUp Maven in Jenkins
# Create Maven Project in Jenkins
# Add Project Goal

//Local Repository
https://www.youtube.com/watch?v=o2gAw929--g

//GIT Repository
https://www.youtube.com/watch?v=GlQHS7FdVGM

https://maven.apache.org/

Apache Maven 3.6.3

C:\apache-maven-3.6.3

## Form Email Notification Settings:-

STEP-1

Manage Jenkins -> Configure System -> Email Notification

SMTP (Simple Mail Transfer Protocol) Server : smtp.gmail.com

Click on Advance button

Click on "Use SMTP Authentication"
User Name : raghibtest99@gmail.com
Password : zaq1!QAZ
Use SSL	: Click on this	
SMTP Port : 465
Reply-To Address : noreply@gmail.com
Charset : UTF-8

STEP-2

Go to the Jobs -> Configure -> 

Build Settings
E-mail Notification	
Recipients : raghibtest99@gmail.com

Send e-mail for every unstable build

Apply -> Save.

## Schedule a job run :-

Go to the Jobs -> Configure -> 

Build Triggers -> Click on "Build periodically" ->

50 * * * *