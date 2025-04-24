# SE_Project_Phase1_Team10
Software Engineering Project

# Team Information
## Team Name: Team 10

## Team Leader:
- **Name:** Patrik Xhaferri
- **GitHub Username:** MegaPeti

## Team Members:
1. Arjel Sulollari - GitHub: Arjel21, Email: asulollari22@epoka.edu.al
2. Nikol Deçolli - GitHub: Nikol20022, Email: ndecolli22@epoka.edu.al
3. Patrik Xhaferri - GitHub: MegaPeti, Email: patrikxhaferri@gmail.com, pxhaferri22@epoka.edu.al

# Project Details

## Project Title: Check in/ Check out system

## Problem Statement:
A company was facing issues with keeping track of its employees’ activity and attendance at work. They still relied on paper-based logs so that left a lot of room for human errors, false reports, misplaced errors and what matters most it was an every-day time consuming process. Without an automated system, the company was prone to unauthorized check-in and false logs. Also, management struggles to make analytics about an employee’s attendance at work, tardiness or day-offs due to the absence of historical data or loss of papers through the time.

## Solution Proposed:
To address the problem of the current manual system, we suggest a Check in/ Check out system application that ensures no bypass, accurate tracking and enhanced security that also leads to fair payroll for all employees at the end of the month regarding their regular attendance, tardiness, days off, sick leave, overtime etc.

## Project Scope:
- **Aim:** This project will assist with automating the access management efficiently to reduce manual errors, improve the record accuracy through secure user authentication and providing real-time tracking and reporting

- **Main Objectives:**
1. Minimize manual logging and administrative efforts
2. Create a user-friendly application for easy access and management
3. Improve security and access control
4. Enable real-time monitoring and data accuracy
5. Automate the check-in/check-out process

## Application Description:

#### **Requirements**
- User registration and authentication
- Attendance/activity tracking
- Automated check-in/check-out
- User-friendly interface

#### **Features**
- User Account Management: Users can log in and manage their profiles.
- Homepage: Selecting whether you are a simple user or admin
- Attendance History: Users can see and export historical records of their check-ins and check-outs from work.
- Change Credentials: Users can issue a request to the management to change username, password or email.
- Employee Management: Admin can add, update or delete an employee's information from the record table.
- Search function: Search for a specific employee through filters.
- Tracking: Admin can track the attendance of all employees.
- Request Form: Admin can accept or decline user's request to change credentials.

#### **Intended Users**
- Employees & staff
- Administrators & managers

#### **Limitations**
- Offline mode
- Multi-language support
- Advanced recognition features

# Roles and Tasks Distribution

## Team Leader:
Patrik Xhaferri (Software Engineer) - Homepage, Filtered search function, User Change Request, UI (shared responsibility), Database (shared responsibility)

## Main Roles and Tasks:
1. Arjel Sulollari (Full-stack developer) - Login, Add/Update/Delete User, Admin Change Request, UI (shared responsibility), Database (shared responsibility)
2. Nikol Deçolli (Full-stack developer & Tester)- Interface table, Export records, Check in/checko out, User History, UI (shared responsibility), Database (shared responsibility)

# Deadline
Submission Deadline: 15.03.2025, 23:59 hours.

# Additional Notes
[Include any additional notes or instructions for the submission.]

# Phase II: User Requirements and Application Specifications
## 1.	Chosen Development Model
For this project, we chose to follow the Agile development model due to its flexibility, adaptability and iterative approach. The reason behind selecting this model is that agile allows for continuous improvement through iterative cycles and getting feedback from the stakeholders allows the system to align with their needs. Being tolerant to adaptability, it allows for frequent and quick adjustments and not to mention that is less prone to risks of major failures since it has early testing and follows an incremental development.
## 2.	User Requirements
#### **a. Stakeholders**
- Employees (end-users) – they will use the system to check in and check out so what they need is a comprehensive, accurate and efficient system
- Managers - what they are looking for is real-time monitoring  and reports so they can supervise the users’ attendance and activity
- IT department - they are aiming to have secure access control and system scalability because they will be responsible for maintaining the system and dealing with troubleshooting
- HR team - based on users’ attendance, they will calculate payroll
- Business owners - they have the final word about approving the system implementation and budget
#### **b. User Stories**
| User Type | User Story | Requirement | Benefit |
| --- | --- | --- | --- |
| End-user | “As an end user, I want to check in quickly using my QR code, so that I don’t waste time in long queues or manual logbooks.” | The system should provide a QR code scanning identification, Instant logging of check-in time | Time-efficient, Reduces human error |
| Manager | “As an administrator, I want to see a real-time dashboard of check-ins and check-outs, so that I can track attendance in real-time.” | A live dashboard displaying check-ins/check-outs, Being able to filter users by categories | Improves management overseeing
| HR manager | “As an HR manager, I want to calculate payroll based on accurate logs of users’ attendance, tardiness, day offs, sick leaves etc.” | Reports must include total work hours, late arrivals and absence, A form of documentation by exporting | Reduces errors, Compliant to work hour policies |
## 3.	Functional Requirements
#### **a. Brief Description**
- User Account Management: Users can log in through QR code identification and manage their profiles.
- Homepage: Selecting whether you are a simple user or admin.
-	Attendance History: Users can see and export historical records of their check-ins and check-outs from work.
-	Change Credentials: Users can issue a request to the management to change username, password or email.
-	Employee Management: Admin can add, update or delete an employee's information from the record table.
-	Search function: Search for a specific employee through filters.
-	Tracking: Admin can track the attendance of all employees.
-	Request Form: Admin can accept or decline user's request to change credentials.
#### **b.	Acceptance Criteria**
#### **User Account Management**
-	Users can log in using QR code authentication
-	Users can view and change their profile information
-	After successful/failed login, the system shows a clear message or redirects user to another page
#### **Homepage**
-	When entering the system, users see an option to choose between “User” or “Admin” access
-	Selection redirects to the corresponding panel, User Account Management or Admin Panel
-	Unauthorized users can not access the Admin Panel
#### **Attendance History**
-	Users can view their daily check-in/check-out records
-	User can export attendance records in Excel
-	Data is automatically updated and cannot be modified by users
#### **Change Credentials**
-	Users can request to change their username, password or email through a request form to strengthen their security
-	The system forwards the request to the admin for approval
-	User receives notification about the status of their request 
-	Depending on the action, the system updates the credentials and sends a confirmation message
#### **Employee Management (Admin Panel)**
-	Admin can add new user with all necessary information
-	Admin can update employee records 
-	Admin can delete an employee’s record 
-	Admin can view all attendance records for each user
#### **Search Function**
-	Admin can search for a user by name, age, gender or role using filters
-	Results are displayed without reloading the page
## 4.	Non-Functional Requirements
#### **a. Brief Description**
The system should have an overall great performance and ease the experience of the users. As times go by, if there is any problem, the IT department will not struggle with managing the system and fixing its components in a short time. It will use security best practices and we will make sure the performance does not decline in higher workloads. And it should work in different environments as well
#### **b.	Acceptance Criteria**
-	Each page must load within 2 seconds 
-	Users shall be equipped with QR codes to authenticate themselves
-	The system should be able to scale up to around 100 concurrent users
-	The system must perform without fatal errors in 95% of the use cases during a month
-	The most frequently used features must be reached with minimal navigation
## 5.	Application Specifications
#### **a. Database Model**
![image](https://github.com/user-attachments/assets/6acca76d-9fa1-4887-ac7e-9ce466e7f95b)
#### **b. Technologies Used**
- Java – our main backend programming language
- JFrame, Java Swing – frontend frameworks
- Springboot (optional) – Java web framework
#### **c. User Interface Design**
![image](https://github.com/user-attachments/assets/da6b03f8-5914-49ee-8c75-7e4fe5e2327d)
![image](https://github.com/user-attachments/assets/282f6799-f3e2-4d8f-83c3-0ca5b801deee)
![image](https://github.com/user-attachments/assets/43b8b224-a6d4-49f8-b974-fe0957ea2f73)
#### **d. Security Measure**
#### **Authentication**
- QR code-based login:   Users must scan a unique QR code to log in securely
-	Account lockout:   If a user enters the wrong password 5 times their account gets locked for 10 minutes to prevent brute force attacks
#### **Data encryption and storage**
- Database encryption:  Sensitive data like passwords will be hashed and salted
#### **System monitoring**
- Automatic session expiry:  If a user stays idle or inactive for 15 minutes they will be automatically logged out to prevent unauthorized access
# Deadline
Submission Deadline: 26.03.2025, 23:59 hours

# Phase III: Software Design and Modeling 
## Software Architecture
#### **Software Architecture**
The system is going to be a Java-based desktop application
- User Interface: Using Java Swing, it enable users to get around the system and direct actions to the controller.
-	Controller: Takes the input form the interface and controls the logic by calling the right methods.
-	Business Logic: Contains the logic of validating users and recording timestamps.
-	Data Access Layer: Communicates with the database or file system to store and retrieve check-in/out records and user data.
-	Model: These are Java classes with attributes and getters/setters.
-	Database: Stores information such as users and check-in history.
#### **Component diagram**
![image](https://github.com/user-attachments/assets/8db23d39-8bc0-4fb8-9356-61a59abaf55c)
### **Detailed Design**
#### **Class diagram**
![image](https://github.com/user-attachments/assets/dad3542b-fcfb-415d-b48c-16ee2a35794e)
#### **Sequence diagram**
![image](https://github.com/user-attachments/assets/c65175cc-aa3d-47a4-b843-5463d417c32a)
#### **Database design**
![image](https://github.com/user-attachments/assets/13ed5293-28bc-4672-8a4d-5f0a592992a6)
### **Modeling**
#### **Use case diagram**
![image](https://github.com/user-attachments/assets/a15ecd71-f904-4d40-805b-0f84a0ffafe4)
#### **Activity diagram**
![image](https://github.com/user-attachments/assets/0052b310-45dc-453a-8b47-b9c4bc654275) ![image](https://github.com/user-attachments/assets/12c8b3b6-2991-4c50-aca8-b25bd868fa4f) ![image](https://github.com/user-attachments/assets/b0dccec1-2b0a-49d8-9883-357d3035e719) ![image](https://github.com/user-attachments/assets/ac572956-8bca-4235-8be2-033352fc85ea) ![image](https://github.com/user-attachments/assets/f8fcf6ca-9a19-4113-917c-78a0bb13599b)
#### **State diagram**
![image](https://github.com/user-attachments/assets/43942aa4-84af-4988-ba29-329bc7b12cdc) Admin Panel
![image](https://github.com/user-attachments/assets/d2acccb6-1803-41a9-8452-984441b387d2) Employee Panel















