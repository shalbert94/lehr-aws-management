# lehr-aws-management
Guides for managing an Amazon Web Services (AWS) instance.


Please note that all work was performed using:

1. A desktop with an Ubuntu operating system

2. Instances that have an Ubuntu AMI (i.e. they are Ubuntu instances)

Steps for putting your Shiny application on an AWS server:

1. open-aws-console = Enter the AWS EC2 console. 

2. launch-instance = Creating a new instance. 

3. connect-to-instance = Enables you to manage an instance using the "Terminal" desktop applicaiton

4. opensource-shiny-server-installation = Setup Shiny Server on the AWS instance

5. organize-shiny-application-directory = Prepare your shiny application to be uploaded to the shiny server 

6. desktop-to-shiny-server-file-transfer = Transfer an application's directory (entire folder) from a desktop to the Shiny Server

7. shiny-application-log = Enables Shiny Server to save crash logs for applications. 
    Enables you to learn why an application crashed.
    
8. install-r-packages = Install R packages on Shiny Server.
    Enables you to control the R environment through the Terminal desktop application.
    
9. track-instance-usage = Make sure your instance is running 

10. resize-instance = Increase or decrease your instance's performance to match demand
