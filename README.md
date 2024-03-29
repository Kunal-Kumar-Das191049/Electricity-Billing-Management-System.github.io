# Electricity Billing-Management-System
# Table of Contents

1. [Demo](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/README.md#demo)
2. [Description](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/README.md#description)
3. [Objective And Aim](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/README.md#objective-and-aim)
4. [Sections](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/README.md#sections)
5. [Java Classes](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/README.md#java-classes)
6. [Conclusion](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/README.md#conclusion)
7. [License](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/README.md#license)
8. [Credits](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/README.md#credits)
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
    This Application can serve the Electricity Department by computerizing the billing  system by paying 
    electricity bill  of a specific time online.It make the Overall billing system easy to access and 
    effective for the users.

## Sections 

### 1. Login Page
         It consists of Username and Password which the existing admin/consumers can use to login into
         the main Dashboard of this application.
         
### 2. Signup Page         
        It consists of Username,Password and meter number which the  admin/consumers can use to create
        their account in order to login into  the main Dashboard of this application.
 
### 3. Menu
        1. New Customer:-      Admin can add new consumers by filling the necessary details such as 
                               name,email id,Phone number,Address etc. 
        
        2. Customer Details:-  Admin can view the details such as Customer Name ,Meter number, 
                                Address etc of all consumers.
                               
        3. Deposit Details:-   Admin can view,search and print the electricity bill deposit details
                               such as meternumber,month,units,total bill and status by sorting the
                               meter number and month from the scroll panel. 
                                
        4. Calculate Bill:-    Admin can calculate the electricity bill of any consumers by selecting 
                               the meter number andmonth from the scroll panel and filling the units 
                               consumed in that particular month.
                            
### 4. Utility
        Admin and consumers can use utilities/applications like NOTEPAD,CALCULATOR and WEB BROWSER according 
        to their requirement.
              
### 5. Information
        1. Update Information:- consumers can update their any details and information.
         
        2. View Information:-   consumers can view their details.
 ### 6. User
         1. pay Bill:-      consumers can pay their electricity bill by selecting the month from the
                            scroll panel. 
         
         2. Bill Details:-  consumers can view their bill details such as meter no, month,total bill
                            and status.
 ### 7.Report
          Generate bill:- consumers can generate their electricity bill by selecting the desired month 
                           from the scroll panel.
           

       
 ## Java Classes
 
 ### 1. Conn Class
           This class establishes a connection between NetBeans IDE and MySQL.It is done by adding
           MySQL_connector_java_8.0.26.jar file.

 ### 2. Login Class
            It consists of Username and Password which the existing admin or consumers can use to login into
            the main Dashboard of this application.
            
        
         
       
![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/login.Screenshot%20(3032).png)
 ### 3.Signup class
          It consists of Username,Password and meter number which the  admin/consumers can use to create
          their account in order to login into  the main Dashboard of this application. 
 ![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/create%20account.Screenshot%20(3033).png)         
 ### 4.Project Class[Main Dashboard]
          This class consists of different options in the header such as:-
             If login as Admin           If login as Customer 
                1. Menu                     1.Information 
                2. Utility                  2.user
                3. Logout                   3.Report
                                            4.Logout
                                       
                                              

          
                                      
![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/main%20dashboard.Screenshot%20(3069).png)

   ### 5.NewCustomer Class
          Here the admin can  add the details of a new customer.It has 7 textfields as follows:-
               1.Customer Name                    
               2.Meter number                
               3.Address                    
               4.City               
               5.State
               6.Email 
               7.Phone number


![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/New%20customerScreenshot%20(3035).png)

 ### 6.CustomerDetails Class
         Admin can view the details such as Customer Name ,Meter number, Address etc of all consumers.
                               

![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/customer%20details.Screenshot%20(3073).png)

### 7.DepositDetails Class
           Admin can view,search and print the electricity bill deposit details such as meter number,
           month,units,total bill and status by sorting the meter number and month from the scroll panel. 
![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/depositdetails.screenshot.png)

### 8.CalculateBill Class
          Admin can calculate the electricity bill of any consumers by selecting the meter number and
          month from the scroll panel and filling the units consumed in that particular month.


![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/calculatebill.screenshots.png)

### 9.UpdateInformation Class
         consumers can update their any details and information.

![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/updateinformation.screenshot.png)

### 10.ViewInformation Class
         consumers can view their details.
          
![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/viewinformation.screenshot.png)
### 10. PayBill class
        consumers can pay their electricity bill by selecting the month from the scroll panel. 
![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/paybill.Screenshot%20(3077).png)
### 11. BillDetails class
          consumers can view their bill details such as meter no, month,total bill and status.
![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/billdetails.screenshot.png)
### 12. GenerateBill class
          consumers can generate their electricity bill by selecting the desired month from  the scroll panel.
![Development and Design](https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/generatebill.Screenshot%20(3043).png)
## Conclusion
         This application can help the electricity department in computerizing the billing
         system by paying the electricity bill of a specific time online.It will save time 
         of consumers .It makes the Overall billing system easy to access and
         and effective for the users.
         
        
## License
   ### MIT LICENSE
link:https://github.com/Kunal-Kumar-Das191049/Electricity-Billing-Management-System/blob/master/LICENSE
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
