# User Setup with Non-Interactive Shell

Create a user name "javed" on app server 2 with non interactive shell 

Step1:Connect to app server 2 using 
Command : ssh user@ipaddress
Put password 

Step2:Use command to create user with non interactive shell access .
Command : sudo useradd -m -s /sbin/nologin javed 

Step3:Try ssh app server 2 with user javed 
Message : This account is currently not available.
