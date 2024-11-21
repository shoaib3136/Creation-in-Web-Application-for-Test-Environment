 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
  ## AIM: 
  To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT:
Creating a web application for a test environment is essential to provide developers and testers with a dedicated platform to simulate, test, and validate software functionalities. The challenge lies in building an easy-to-use,   
scalable, and efficient application that supports realistic testing scenarios, automates workflows, and ensures smooth collaboration while minimizing setup and maintenance efforts.

## ALGORITHM
 ### Steps 1:
 Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
 ### Steps 2:
 Connect to the instance using SSH and install a web server like Apache
 ### Steps 3:
 Create a simple HTML file in the server's default directory with basic content for testing.
 ### Steps 4:
 Access the instance's public IP in a browser to verify the HTML page is displayed.
## COMMANDS
1. To install httpd:
```
yum install httpd -y
```
3. To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
4. Create a simple HTML page :
```
cd /var/www/html
```
5. Create a simple HTML page :
```
cd /var/www/html
```
6. test.php
```   
  <!DOCTYPE html>
  <html lang="en">
  <head>
     <title>MY FIRST PHP!</title>
  </head>
  </body>
  </html>
```
## OUTPUT
### REG NUMBER: 212222240094
### NAME: Shaik Shoaib Nawaz
1. Terminal:
 ![image](https://github.com/user-attachments/assets/1bfb5a04-0929-4a3c-9ffb-cefb1a2b9228)
2. Website:
![image](https://github.com/user-attachments/assets/9aa02b87-f288-4552-860f-40c7820cee46)

## RESULT
Thus the web application for test environment has successfully been created and executed.


 

  


