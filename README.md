# internship_project
# Human Resource Management System ERP Module using Django
By: BizzAppDevSystems Pvt. Ltd.


# Harshrajsinh Solanki (18BCE234) 
# Kunj Thaker (18BCE240)

 
## Abstract:  
●	The paper titled “HUMAN RESOURCE MANAGEMENT SYSTEM” is basically concerned with managing the Administrator of HUMAN RESOURCE Department in a company. A Human Resource Management System (HRMS), refers to the systems and processes at the intersection between human resource management (HRM) and information technology. It merges HRM as a discipline and in particular its basic HR activities and processes with the information technology field, whereas the programming of data processing systems evolved into standardized routines and packages of enterprise resource planning (ERP) software[1]. The main objective of this paper is to reduce the effort of Administrator to keep the daily events such as attendance, projects, works, appointments, etc. 
●	This document deals with the process of identifying the employees, recording their attendance hourly and calculating their effective payable hours or days. This paper should maintain the records of each and every employee and their time spend in to company, which can be used for performance appraisal. Based on that transfer, removal, promotion can be done. 
 
Keyword: Human Resource, Administrator, Employee
Technology used: Django(python), HTML, CSS, JavaScript
Database: mysql
 
I.	Introduction 
The document  is used to maintain efficiently the HR department schedule of any type of company. In larger organization, employees are large. At that time this paper is useful and helpful. HR Management system is not only becomes a desire of the company but it becomes the need of the company. The Administrator gets into the system using admin name and a password. 
1.	 Advantages 
1.	Easy access to the data 
2.	The new system is more user-friendly, reliable and flexible. 
3.	Data alteration is easy. 
4.	Maintenance of the project is easy. 
5.	Reduced manual work. 
6.	Timely Report generation. 

 
# ER Diagram

The main objective of this document is to reduce the effort of administrator to keep the daily events such as payroll, recruitment, attendance , and employees’ details. It consists of seven modules. 

They are:- 
## 1.	Login 
## 2.	Employee Details 
## 3.	Departments 
## 4.	Recruitment (Candidate Application Form) 
## 5.	Attendance 
## 6.	Leave Management:
## 7.	Payroll
  
Fig 1: Overview of Human Resource Management Systems 
 
     1.2 Employee Details 
 
Employee Details module is used to maintain the employees’ details such as adding new employee, modifying the existing employee and deleting the existing employee. When a new employee is selected from the resume tracking, all the details are to be entered and maintained in the database.
 
  
 Details The employee details contains three kind of information. 
1.	Personal Information 
2.	Contact Information 
3.	Employee Status 
4.	Employee Department
5.	Employee Attendance
In the personal information, it consists of the information about the employee name, employee id, nationality, etc. In the contact information, it consists of the information about the employee address, phone numbers, etc, 
In the employee status, it consists of the information about the status of the employee, supervisor name, department, etc. 
 
1.3 Departments:
Manage Department – For the department, The admin can add, edit, and delete department information.

Admin also checks employee names for particular departments.
 
  1.4 Recruitment (Candidate Application Form):
Manage Recruitment – For the recruitment, the admin can see a list of all recruitment and process each one.
 
  1.5 Attendance:
 
Data Flow Diagram for attendance management system
 
  1.6  Leave Management 
 
This module contains the information about the employees leave details. There are three kinds of leave which are sick leave, vacation, and holiday. 
 
There are fixed amount of days that are allocated for each type of leave and the database of leave  details are maintained by the organization. The details includes number of days, period, total number of leave taken by that employee upto that date and number of days that are remaining. 


 
 
       1.7 PAYROLL 
In the payroll module, it consists of the information about the employee salary details such as basic pay, allowances, deductions and calculate the gross pay and net pay from the given allowances and deductions. 
  
Fig 3 : Overview of Payroll Details 


All the employees’ pay details are maintained by the HR manager. The main function of this payroll module is to maintain the employee pay information. 


 
## II.	Tables 
2.1 LOGIN 

 
 
 
2.2 EMPLOYEE 
  

2.3 LEAVE MANAGEMENT

 
 
 
 
## III.	 Input Key 
The goal of input key is to input data as accurately as possible. Here inputs are designed effectively so that the error made by operation is minimized. The input to the system has been designed and coordination in such way that there format is similar in all forms. Forms are designed in such way that relevant information is grouped together and they are placed on a single frame, so as to access easily. At the time of data entry the verification and validation of the data were done. 
Input key is the most part of the overall system design, which requires very careful attention. Often the collection of the input data is most expensive part of the system. Many errors may occur during the phase of the design. So to make the system study, the inputs given by the user is strictly validated before making a manipulation with it. 
 
## IV.	 Output Key 
The output key is another very important phase. The outputs are mainly used to communicate with the user, processing the input data given by the user. It is documented in each stage of the project to ensure free output. The output screens are designed in very simple and easy to understand format. The quality, urgency and the frequency of outputs should be taken into consideration. All user option is presented in well-formatted  forms. The quality refers to the way by which the output is presented to the user. 
The reports can be used for day-to-day functioning of the business as well as management information. The reports, if generated with the specific report criteria and in a timely manner, help in operational efficiency, detecting and minimizing of errors as well as provide the pointers towards control weakness. 
 
Output screen are designed in such a way that no ambiguity arises. Output data is presented in a well-formatted way. The required information is printed on the report in the specified format.


V.	Testing Phase 
1.	Home Page 
![image](https://user-images.githubusercontent.com/63163693/124353071-cc9ffa80-dc21-11eb-833d-571eaccf8dc6.png)


2.	Candidate Application Form 
![image](https://user-images.githubusercontent.com/63163693/124353080-dcb7da00-dc21-11eb-968b-ff680001f4c0.png)


3.	Administrator Login Module 
![image](https://user-images.githubusercontent.com/63163693/124353087-efcaaa00-dc21-11eb-883c-49733171f893.png)

 
4.	Administrator Registration 
![image](https://user-images.githubusercontent.com/63163693/124353094-fc4f0280-dc21-11eb-90f6-952c6fbdd022.png)


5.	Add Department Module
![image](https://user-images.githubusercontent.com/63163693/124353099-06710100-dc22-11eb-8847-4a4f1aa4667e.png)


6.	Add New Employee Module 
![image](https://user-images.githubusercontent.com/63163693/124353107-1688e080-dc22-11eb-8f69-e6b48b70acd7.png)


7.	Employee Profile 
![image](https://user-images.githubusercontent.com/63163693/124353110-1f79b200-dc22-11eb-9786-67bfa0b213d2.png)


8.	Dashboard 
![image](https://user-images.githubusercontent.com/63163693/124353118-29031a00-dc22-11eb-80fd-41c644a46f2b.png)


9.	Employee Attendance Module 
![image](https://user-images.githubusercontent.com/63163693/124353122-30c2be80-dc22-11eb-8b62-330b98acf35a.png)


10.	Leave management Module 
![image](https://user-images.githubusercontent.com/63163693/124353126-3ae4bd00-dc22-11eb-920e-3307676de8d8.png)


11.	Payroll Management 
![image](https://user-images.githubusercontent.com/63163693/124353130-433cf800-dc22-11eb-9371-aa9e620e5e55.png)

  
12.	Department Information 
![image](https://user-images.githubusercontent.com/63163693/124353133-4a640600-dc22-11eb-87e3-bbabcb8d84e1.png)


13.	 Recruitment Module 
![image](https://user-images.githubusercontent.com/63163693/124353138-54860480-dc22-11eb-8886-2d89c562be79.png)


# How to run:
## pip install -r requirements.txt
## python manage.py makemigrations
## python manage.py migrate
## python manage.py runserver
 



