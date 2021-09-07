# Electricity Billing-Management-System
# Table of Contents

1. [Demo](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/README.md#demo)
2. [Description](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/README.md#description)
3. [Objective And Aim](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/README.md#objective-and-aim)
4. [Sections](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/README.md#sections)
5. [Java Classes](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/README.md#java-classes)
6. [Conclusion](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/README.md#conclusion)
7. [License](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/README.md#license)
8. [Credits](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/README.md#credits)
## Demo

Link:https://drive.google.com/file/d/1T5EuIp6oH6toU9vR_P3b8AX1DHMCemWe/view?usp=sharing


![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/demo.png)

## Description

Electricity Billing Management System is a Desktop based application which is developed by using JAVA language on Netbeans12 IDE using the concept of SWING.The database used in this project is MySql.
👉Admins/Consumers can create their account in order to login into the main dashboard of this Application.

👉Admins can ADD,VIEW the details of all consumers.

👉Admins can CALCULATE  the electricity bill of all consumers.

👉Admins/Consumers can use utilities such as NOTEPAD,CALCULATOR,WEB BROWSER.

👉Consumers can UPDATE/VIEW their Information or Details.

👉Consumers can PAY and GENERATE their Electricity Bill online.



## Objective and Aim 
    This Application can serve the Electricity Department by computerizing the billing  system by paying  electricity bill of a specific time online.It make the Overall billing     System easy to access and effective for the users.

## Sections 

### 1. Login Page
         It consists of Username and Password which the existing admin can use to login into
         the main Dashboard of this application.
         
         

### 2. Employee Details
        It Consists of 4 Columns:-
              1. Add 
                 
              2. View
                 
              3. Remove
               
              4. Update
                
              
 ### 2. Add Employee                
            Admin can add details of a new employee by filling the 
            necessary details like:-
            Name              Job Post          Phone
            Address           Employee ID       Education
            Age               Father's name     Aadhar No
            Email ID          Date Of Birth 
                       
 ### 3. View
            It consists of Employee ID which the admin can enter to view details of a particular employee
            in the Print window.
 
 ### 4.Remove
            Here the Admin can remove records of any Employee by entering their Employee ID.
           
 ### 5.Update
            Here the Admin can Update the details of any Employee by entering the Employee ID in the
            Search Window.
       
 ## Java Classes
 
 ### 1. Conn Class
           This class establishes a connection between NetBeans IDE and MySQL.It is done by adding
           MySQL_connector_java_8.0.26.jar file.
 ### 2. Front_Page Class
           It is the first window/page of this application consists of a blink string
           "EMPLOYEE MANAGEMENT SYSTEM" and one button i.e"CLICK HERE TO CONTINUE".
 ![Development and Design](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/Front%20page.png)
 ### 3. Login Class
            It consists of Username and Password which the existing admin can use to login into
            the main Dashboard of this application.
            
            Username and Password can be changed in the database.
         
       
![Development and Design](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/login.png)
 
 ### 4.Details Class[Main Dashboard]
          This class consists of different options in the header such as:-
                  
                  1.Add                   
                  2.View                   
                  3.Remove                    
                  4.Update                           
                                       
                                              

          
                                      
![Development and Design](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/Main%20Dashboard.png)

   ### 5.Add_Employee Class
          Here the admin can  add the details of a new customer.It has 11 textfields as follows:-
               1.Name                    8.Date of Birth
               2.Address                 9.Phone
               3.Age                     10.Education
               4.Email ID                11.Aadhar No
               5.Job Post
               6.Employee ID
               7.Father's name


![Development and Design](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/Add%20details.png)

 ### 6.View_Employee Class
          It consists of Employee ID which the admin can enter to view details of a particular employee
          in the Print window.
 

![Development and Design](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/viewemployee.png)

### 7.Print_data Class
           Admin can also PRINT details/records of any employee by entering Employee ID in the view employee window.

![Development and Design](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/print.png)

### 8.Remove_Employee Class
        Admin can REMOVE details/records of any employee by using Employee ID of that particular employee.


![Development and Design](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/Remove%20Employee.png)

### 9.Search_Employee Class
          It consists of  a textfield i.e Employee Id which the Admin has to enter to update the details
          of a particular Employee. 

![Development and Design](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/Search%20employee.png)

### 10.Update_Employee Class
          Here the Admin can Update the details of any Employee by entering the Employee ID in the
          Search Window.
          
![Development and Design](https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/Update_Employee.png)

## Conclusion
         This application can help the organizations to maintain the the records of their Employees rather than 
         using pen,paper and registers.
         
         Since it is a paperless mode of maintaining records so it is also ENVIRONMENT FRIENDLY as well as CLUTTER
         FREE for the orgainzations.
## License
   ### MIT LICENSE
link:https://github.com/Kunal-Kumar-Das191049/Employee-Management-System/blob/master/LICENSE
        MIT License

Copyright (c) 2021 Kunal Kumar Das

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Credits
   * Google Images Download.
   * Net Beans IDE
   * MY SQL
        
        This project Wouldn't have been possible without these tools.It Saved my enormous  amount of time while collecting the data. 
Electricity Billing Management System is a Desktop Application which can serve the Electricity Department by computerizing the billing  system by paying  electricity bill of a specific time online
